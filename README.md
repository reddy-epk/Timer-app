Building a **Digital Timer App** 
### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/digital-timer-output.gif" alt="digital timer output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)" />
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px), Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/digital-timer-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/digital-timer-lg-output.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>


<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/DigitalTimer/index.js`
- `src/components/DigitalTimer/index.css`
</details>

### Quick Tips

<details>
<summary>Click to view</summary>
<br>

- Use the `box-shadow` CSS property to apply the box-shadow effect to containers

  ```
    box-shadow: 0px 4px 16px 0px #bfbfbf;
  ```

  <br/>
  <img src="https://assets.ccbp.in/frontend/content/react-js/box-shadow-img.png" alt="box shadow" style="width:200px" />

- Use `Math.floor()` function that returns the **largest integer less than or equal to a given number**

  ```js
  console.log(Math.floor(5.95)); // output: 5
  ```

- Use the `background-position` CSS property to set the starting position of a background image
  ```
  background-position: center;
  ```

</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/digital-timer-elapsed-bg.png](https://assets.ccbp.in/frontend/react-js/digital-timer-elapsed-bg.png)
- [https://assets.ccbp.in/frontend/react-js/play-icon-img.png](https://assets.ccbp.in/frontend/react-js/play-icon-img.png) alt should be **play icon**
- [https://assets.ccbp.in/frontend/react-js/pause-icon-img.png](https://assets.ccbp.in/frontend/react-js/pause-icon-img.png) alt should be **pause icon**
- [https://assets.ccbp.in/frontend/react-js/reset-icon-img.png](https://assets.ccbp.in/frontend/react-js/reset-icon-img.png) alt should be **reset icon**

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #ffffff ; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #cffcf1 ; width: 150px; padding: 10px; color: black">Hex: #cffcf1</div>
<div style="background-color: #1e293b ; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>
<div style="background-color: #0f172a ; width: 150px; padding: 10px; color: white">Hex: #0f172a</div>
<div style="background-color: #defafe ; width: 150px; padding: 10px; color: black">Hex: #defafe</div>
<div style="background-color: #00d9f5 ; width: 150px; padding: 10px; color: white">Hex: #00d9f5</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

> ### _Things not_to change_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.

