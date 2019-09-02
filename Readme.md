var student = [
    {
        name:"christy tiwa",
        age:26,
        address:"nassarawa gwom",
        tribe:"yoruba",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.69,
        department:"compuer science",
        level:300,

    },
    {   name:"ifeoma",
        age:25,
        address:"dogon dussai",
        grade:[20,30,40,50,60,70],
        tribe:"igbo",
        gender:"female",
        height:1.6,
        department:"compuer science",
        level:300,

   },

    {

        name:"gift",
        age:24,
        address:"angwan dussai",
        tribe:"igala",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.56,
        department:"computer science",
        level:300,

    
    },{

        name:"mark",
        age:26,
        address:"rayfeild",
        tribe:"idoma",
        gender:"male",
        grade:[20,30,40,50,60,70],
        height:1.8,
        department:"computer science",
        level:300,
    },

    {
        name:"charles",
        age:24,
        address:"katako",
        tribe:"igbo",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:1.8,
        department:"computer science",
        level:300,
    },

    {

        name:"tosin",
        age:24,
        address:"farin gada",
        tribe:"yoruba",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.4,
        department:"computer science",
        level:300,
    },

    {
        name:"kelvin",
        age:23,
        address:"maza road",
        tribe:"shandam",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:1.4,
        department:"computer science",
        level:300,
    },
    
    {

        name:"nanbal",
        age:26,
        address:"legislative",
        tribe:"mupul",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:1.68,
        department:"computer science",
        level:300,

    },

    {
        name:"josephine",
        age:23,
        address:"odus",
        tribe:"eggon",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.5,
        department:"computer science",
        level:300,


    },

    {
        name:"susan",
        age:26,
        address:"farin gadan",
        tribe:"idoma",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.54,
        department:"compuer science",
        level:300,
    },

    {


         name:"elizabeth",
        age:25,
        address:"farin gada",
        tribe:"ibibio",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.5,
        department:"computer science",
        level:300,

    },
    
    {
         name:"uzaifat",
        age:24,
        address:"dodo street",
        tribe:"maghavul",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:1.5,
        department:"computer science",
        level:400,

    },
    
    {

        name:"maryam",
        age:27,
        address:"behind pts",
        tribe:"igala",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:"1.5",
        department:"computer science",
        level:300,


    },

    {
        name:"martins",
        age:24,
        address:"odus",
        tribe:"kargoro",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:1.8,
        department:"computer science",
        level:300,

    },
    
    { 

        name:"paul",
        age:27,
        address:"ray feild",
        tribe:"akwanga",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:1.7,
        department:"computer science",
        level:300,

    },
    
    {
        name:"joy",
        age:23,
        address:"ring road",
        tribe:"edo",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.58,
        department:"computer science",
        level:300,
    },

    {


        name:"deborah",
        age:21,
        address:"odus",
        tribe:"bassa",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.6,
        department:"computer science",
        level:300,

    },
    
    {

        name:"peter",
        age:24,
        address:"furaka junction",
        tribe:"yoruba",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:"1.85",
        department:"computer science",
        level:300,

    },
    
    
    {
        name:"yohanna",
        age:25,
        address:"angwan rukuba",
        tribe:"afizere",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.78,
        department:"computer science",
        level:300,

    },
    
    {
        name:"nanret",
        age:24,
        address:"maza street",
        tribe:"maghavul",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.4,
        department:"computer science",
        level:300,

    },    

    {
       name:"victoria",
        age:24,
        address:"forestry",
        tribe:"berom",
        grade:[20,30,40,50,60,70],
        gender:"female",
        height:1.56,
        department:"computer science",
        level:300,

    },
    
    {

        name:"steve",
        age:24,
        address:"heaven street",
        tribe:"igbo",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:"1.8",
        department:"computer science",
        level:300,

    },
    
    {
        name:"ponfa",
        age:24,
        address:"ring road",
        tribe:"tarrok",
        grade:[20,30,40,50,60,70],
        gender:"male",
        height:"1.6",
        department:"computer science",
        level:300,

    }
];
var max =0;
students.forEach(function(value){
    if(maxa< value.height){
        max = value.height
    }
    // console.log(value.height);
});
console.log(max);
var studentA = student.filter((student)=>student.height == max);
console.log (studentA);