# sunrise_urban_sounds_classification

## GlobalAI Hub project


In this project, ``` the UrbanSounds8K dataset ``` was used to make the classification of the sounds heard in the cities.
The libraries used in this project were imported and saved in the classes they belong to by using the ready-made spectrograms for the audio files.

```
A numeric identifier of the sound class:

0 = air_conditioner

1 = car_horn

2 = children_playing

3 = dog_bark

4 = drilling

5 = engine_idling

6 = gun_shot

7 = jackhammer

8 = siren

9 = street_music
```



Resizing was done by preprocessing the audio files that were converted to images.
By keeping the images in the list, X and Y train, validation and test data of this list were created.
With these created data, modeling and machine training was started.

### Results

- Loss value was determined as 1.1137

- Test accuracy value was determined as 0.7542.
