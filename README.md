var names = ["Mario","Nick", "Zack","Elvis","Dom"];// The list of names in the list 
var name = "Zack"// Here is the name we are looking for

var pos = names.indexOf(name);//The variable will scan for decalred variable "name"

if(pos >=0){//if condition will go through each name starting form Zero to search for the "Zack"
    console.log("The position of name: "+ name +" is "+ pos);// if found print 
} 
else{
    console.log(name+"Name was not found!!");//if not print not found 

}
