function range(start,end){
    var ans = []
    for(i=start; i<=end; i++){
        ans.push(i);
    }
    return ans;
}




function testValues(limit){
     
    //array for inputting 'yu','gi','si'
    valueArray=range(1,limit);
    
    for(x=1;x<=limit;x++){
        
        if(x%2==0){
            
            if(typeof valueArray[x-1] === 'number'){
                valueArray[x-1]="yu"
            }else if(typeof valueArray[x-1] === 'string'){
                valueArray[x-1]=valueArray[x-1]+"-yu"
            }
        }
        if(x%3==0){
            if(typeof valueArray[x-1] === 'number'){
                valueArray[x-1]="gi"
            }else if(typeof valueArray[x-1] === 'string'){
                valueArray[x-1]=valueArray[x-1]+"-gi"
            }
        }
        if(x%5==0){
            if(typeof valueArray[x-1] === 'number'){
                valueArray[x-1]="oh"
            }else if(typeof valueArray[x-1] === 'string'){
                valueArray[x-1]=valueArray[x-1]+"-oh"
            }
        }

    }
    
    return valueArray
    
}

console.log(testValues(100))

console.log(testValues(30))
