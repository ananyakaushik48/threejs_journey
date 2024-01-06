# Chapter 3

#### 1. Setting up a Vite Project
>
> * Create the directory and go into that directory
>> ```bash
>>$ mkdir first_three && cd first_three
>>```
> * Initialise the npm project
>> ```bash
>>$ npm init -y
>>```
> * Install Vite into the project
>> ```bash
>>$ npm i vite
>>```
> * In the ```package.json``` file, replace:
>> ```json
>> "scripts": {
>>    "test":"echo \"Error: no test specified\" && exit 1"
>> }
>>```
> * With this:
>> ```json
>> "scripts": {
>>    "dev": "vite",
>>    "build": "vite build"
>> }
>>```
> * Add the ```index.html``` file and initalise it by typing ```!``` and hitting 'tab'
>> ***Note**: Must have the **Emmet** VSCode extension installed*
