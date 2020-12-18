import * as React from 'react';
import { Text, View, StyleSheet, Image } from 'react-native';
import Constants from 'expo-constants';

// You can import from local files
import AssetExample from './components/AssetExample';

import { Card } from 'react-native-paper';

export default function App() {
  return (
    <View style={styles.container}>
      <Text style={styles.paragraph}>
        Hello world from G15: Ričards Greitāns
      </Text>
      <Text style={styles.paragraph}>
        This is my Ričards Greitāns first React native application!
      </Text>

      <Image
        source={{
          uri:
            'https://www.estlatbl.com/cache/basket/public/remote/http_is-basket-ee/_400x400x1/bw-client-filesXbasketisXpublicXplayer-pictureX2652-v1602073916--0RK3375.jpg',
        }}
        style={{ width: 100, height: 200, borderRadius: 100 / 2 }}
      />

      <Text style={styles.container}>Ričards Greitāns</Text>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
    paddingTop: Constants.statusBarHeight,
    backgroundColor: 'green',
    padding: 8,
  },
  paragraph: {
    margin: 50,
    fontSize: 28,
    fontWeight: 'bold',
    textAlign: 'center',
  },
});
