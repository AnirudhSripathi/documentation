# Welcome
---------------------------------------

## Introduction
This documentation is meant to give information on how to use the endpoints in this api.
If you require examples on how to use this api in your specific language, go to the **Examples** section. There it will guide you through the steps to use the api.

This api only uses the **GET** method for its endpoints

## Why is the api saying "missing x query"
This happens when the api requires an input from the user. This input is used to assign values to specified parameters. For example, the pokedex endpoint requires a pokemon query. This query can be made by adding `?` then the query which is needed, in this case pokemon thus the final url would look like https://some-random-api.ml/pokedex?pokemon=pikachu. Other endpoints might require more than one query such as the canvas color endpoint. This endpoint requires both avatar and color query. To add the avatar simply add `?avatar=https://i.imgur.com/nToSGkI.png` to the end of the url and to add more queries to the link, you ad chain them with `&` thus the end result would look like `&color=%23b5362d` combining all this, we get this url https://some-random-api.ml/canvas/color?avatar=https://i.imgur.com/nToSGkI.png&color=%23b5362d all querys after 2 would use & which will continuously chain resulting in a url such as https://some-random-api.ml/canvas/youtube-comment?username=Telk&comment=hello&avatar=https://i.imgur.com/nToSGkI.png&dark=true​

## How do I get the data sent by the api?
This api will always return either JSON or an image file(canvas endpoints). JSON can be read by using `.` when there is a bracket and if there is a list of things `[1, 2, 3, 4]` you would use `data[which part of the list you want starting from 0]`