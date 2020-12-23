# advancedJavascriptConcepts

<!-- In this we will learn advance javascript concepts -->
<!-- spread operator
rest operator
arrow funstion
forEach
map
filter
reduce
find
sort
DOM selector
ES10 syntax -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Java script Advance concepts</title>
</head>

<body>

    <script>
        //Spread operator
        // spread operator will create a copy of and object or an array
        //eg:

        // let spreadSampleArray = ['Raju', 'Ramu', 'Romu'];
        // let childOfSpreadSampleArray = [...spreadSampleArray];
        // console.log(spreadSampleArray);
        // childOfSpreadSampleArray[2] = 'changed';
        // console.log(childOfSpreadSampleArray);
        // console.log(spreadSampleArray);
        // let neArray = [...childOfSpreadSampleArray, 'changed1'];
        // let neArray1 = [...neArray.slice(0,2)]
        // console.log(neArray);
        // console.log(neArray1);

        // Destrusting

        // let sample = ['value1','value2','value3'];
        // let [v1,v2,v3] = sample;
        // console.log(v1 + v2 + v3);
        // let sampleObj = {
        //     name : 'Visnu',
        //     age: 20
        // }
        // let {name, age} = sampleObj;
        // console.log(name + age);

        // rest
        //     rest operator laso will take a copy of object or Array

        //     let sample = ['value1','value2','value3'];
        // let [v1, ...test] = sample;
        // console.log(v1 +test );
        // let sampleObj = {
        //     name : 'Visnu',
        //     age: 20
        // }
        // let {name, ...rest} = sampleObj;
        // console.log(name + rest );

        // Arrow function

        // normal function

        // function sampleFunctoin(a,b){
        //     return a+b
        // }
        // console.log(sampleFunctoin(10,20))

        // same can be written in arrow function

        // const sampleFunctoin = (a,b) => {
        //     return a+b;
        // }
        // console.log(sampleFunctoin(10,20));

        // const sampleFunctoin = (a,b) =>  a+b;

        // console.log(sampleFunctoin(10,20));

        // 

        // let sample = [{
        //     id : 0,
        //     name : 'Vishnu',
        //     age : 20
        // },
        // {
        //     id : 1,
        //     name : 'Vishnu',
        //     age : 20
        // },
        // {
        //     id : 2,
        //     name : 'Vishnu',
        //     age : 20
        // }]

        // //Normal approach to print this

        // // for(let i = 0; i<sample.length; i++ ){
        // //     console.log(sample[i])
        // // }
        //     //forEach methos
        //     // forEach will take a function with 3 parameter 
        //     // array.forEach(function(value,index,arra){};)

        //     sample.forEach(element => {
        //     console.log(element)
        // });

        // map method

        // map will create a new array from the existing array using the condtion 
        // map also will take a function woth 3 parameters(value,index,array)
        //  let sample = [{
        //         id : 0,
        //         name : 'Vishnu',
        //         age : 20
        //     },
        //     {
        //         id : 1,
        //         name : 'Vishnu',
        //         age : 20
        //  },
        //     {
        //         id : 2,
        //         name : 'Vishnu',
        //         age : 20
        //     }]

        //     let newArray = sample.map((value,index,array)=> value.name);
        //     console.log(newArray)

        //Filer

        // let sample = [{
        //         id : 0,
        //         name : 'Vishnu',
        //         age : 20
        //     },
        //     {
        //         id : 1,
        //         name : 'Vishnu',
        //         age : 20
        //  },
        //     {
        //         id : 2,
        //         name : 'Vishnu',
        //         age : 20
        //     }]

        //     let newArray = sample.filter((value,index,array)=> value.id === 1);
        //     console.log(newArray);

        //reduce method
        // let sample = [1,2,3,4,5,6];
        // let sum = sample.reduce((total,value) => total + value, 0);
        // console.log(sum);


        //find

        // let sample = [{
        //          id : 0,
        //          name : 'Vishnu',
        //          age : 21
        //      },
        //      {
        //          id : 1,
        //          name : 'Vishnu',
        //          age : 20
        //   },
        //      {
        //          id : 0,
        //          name : 'Vishnu',
        //          age : 20
        //      }]

        //      let newArray = sample.filter((value,index,array)=> value.id === 0);
        //      console.log(newArray);

        // sort()

        // let sample = [10, 42, 37, 04, 05, 16];
        // let sorted = sample.sort((firstValue, nextValue) => nextValue - firstValue);
        // console.log(sorted);


    </script>
</body>

</html>
