# Getting Started with Create React App
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
## Available Scripts
In the project directory, you can run:
### `npm start`
**Note: this is a one-way operation. Once you `eject`, you can’t go back!**


# HTML-and-CSS-Note

## image
### background image and a overlay and also cleare text on that image
=>
.apoinmentParent{
    margin-bottom: 100px;
}
.apoinmentParent{
    background-image: url('../../../images/make-appoinment.png');
    position: relative;
    background-position: 0 -400px;
    height:380px;
    top: 100px;
}
.apoinmentParent::before{
    content: "";
    display: block;
    height: 100%;
    width: 100%;
    position: absolute;
    background: rgb(36, 41, 73);
    top: 0;
    opacity: 0.9;
}
.doctor_img{
    height: 530px;
   transform:translateY(-149px);
}
.test1{
    z-index: 1;
}
.appointment-text {
    width:600px;
}
