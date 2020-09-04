
import React, { useState } from 'react';
import { StyleSheet, Text, View, Button } from 'react-native';

function getText (swit) {
    if (swit) {
      return "text change 1";
    }
    return "text change 2";
  }

export default function App() {
  const [outputText, setOutputText] = useState('Open up App.js to start');
  const [text2, changed2] = useState('my second text');
  const [swit, switChange] = useState(false);

  return (
    <View style={styles.container}>
      <Text>{outputText} </Text>
      <Text> {text2} </Text>
      <Button title= "Change Text" onPress={() => {
        switChange(!swit);
        setOutputText(getText(swit));
        changed2(' second changed'); 
      }
      }  /> 
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
});

