# Bubblesort
var array = [3,5,4,8,7]
function bubblesort(array){
var n = array.length;

for(var i = 0; i < n; i++)
  {
    for(var j = 0; j < n; j++)
      {
        if(array[j] > array[j+1])
          {
            var temp = array[j];
            array[j] = array[j+1];
            array[j+1] = temp;
          }
      }
  }
return array
}
console.log(array)
bubblesort(array)
