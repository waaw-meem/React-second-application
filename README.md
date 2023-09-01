<code>
function App () {
    // Event Handler
    // const handleClick = () => {
    //     console.log("Working")
    // }

    // We can also write in this format

    // const handleClick = function() {
    //     console.log("Working")
    // }

    // We can use handleClick() like this if we use this kind of code then it will execute when the component is render
    return (
    <div>

{/* we can write in this format as well
 <button onClick={function() { console.log('New Style')}}>Click Me</button> */}
        {/* 
        We can use in the tag as well

        <button onClick={() => console.log('New Style')}>Click Me</button> */}
        
        {/* // <button onClick={handleClick}>Click Me</button> */}
    </div>
)}

export default App

</code>