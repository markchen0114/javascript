# javascript

# tricket
for(var i=0;i<3;i++) {
        setTimeout(console.log("1i" + i), 500)

        let j=i 
        setTimeout(console.log("1j" + j), 1000)
  }
for(var i=0;i<3;i++) {
        setTimeout("console.log('2i' + "+i+")", 500)

        let j=i 
        setTimeout("console.log('2j' + "+j+")", 1000)
  }
for(var i=0;i<3;i++) {
        setTimeout(() => {console.log("3i" + i)}, 500)

        let j=i 
        setTimeout(() => {console.log("3j" + j)}, 1000)
  }
  
