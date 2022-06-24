react-scroll-up-btn
Source code at https://github.com/maduvhanEMS/react-cards-carousel

Installation
npm install --save react-cards-carousel
or

yarn add react-cards-carousel

Usage
import React from 'react';
import Cards from 'react-cards-carousel';

function Demo(){
return(
<React.Fragment>

<div>
<Cards
                    data={data}
                    startingIndex={0}
                />  
 </div>
</React.Fragment>
)
}

export default Demo;
