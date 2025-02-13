# The New Incredible Machine

> During my bachelor in CS we had this course about multithreading and we have been asked to come up with a project applying what we learned: This is a game attempting to reimagine [*The Incredible Machine*](https://en.wikipedia.org/wiki/The_Incredible_Machine).

> [!WARNING]
> This is a student codebase dating back to 2016, this is a pain to build and to read (in french), sorry 🙏

||
|--|
|Put the 🏀s into the 🪣 using *walls* and *fans* |
|🍎 Multithreaded physical engine (incl. rotation)|
|📐 Edit mode to create your own puzzles|

## Build

```bash
find -name '*.java' > sources.txt
mkdir output
javac -encoding ISO-8859-1 -d output @sources.txt
cp -r src/main/resources/* output
cd ./output
jar cmf ../manifest.mf thethetim.jar com data
```

## Run

```bash
cd ./output
java -jar thethetim.jar
```

## Screens
### Tutorial
![tuto1](https://github.com/EnzoBnl/TheNewTIM/blob/master/src/main/resources/data/tuto1.png)
![tuto2](https://github.com/EnzoBnl/TheNewTIM/blob/master/src/main/resources/data/tuto2.png)

### 40+ puzzles!
![screen11](https://github.com/EnzoBnl/TheNewTIM/blob/master/src/main/resources/data/screens/11.png)
![screen8](https://github.com/EnzoBnl/TheNewTIM/blob/master/src/main/resources/data/screens/8.png)
![screen7](https://github.com/EnzoBnl/TheNewTIM/blob/master/src/main/resources/data/screens/7.png)
