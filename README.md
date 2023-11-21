# 3D-PORTFOLIO
3D portfolio using react.js and tailwind.css
**To start the website**
Use npm command: npm run dev
**To understand the command**
Visit this link https://sebhastian.com/npm-run-dev/
**To add your own 3D image file or render**
Go to public > textures > add scenes with extension gltf or bin or of your choice
Remember to call your scene here 
const Earth = () => {
  const earth = useGLTF('./planet/scene.gltf')
