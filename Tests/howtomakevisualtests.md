# Create Side By Side Visual comparisons using Webview2

As we are making changes to our Flexbox Layout native code, we want to regularly confirm expected behaviours.

A fast an easy way to do this, is to leverage a tool such as https://codepen.io/

With this we can easily view raw html/css, along with it's output, in a clean UI.

## Step by Step

1. Create your html and css files locally, the contents will be transfered later but saving locally allows for use of Git

2. Once you have confirmed your files are displaying the correct layout you wish to compare. Leverage https://codepen.io/ to display your visual test in a browser like: https://codepen.io/matthewmachuca/pen/poLLeGM

3. Use the Webview2 Control to display your test directly in your Test App ex:            
   ```xml
    <controls:WebView2 Source="https://codepen.io/matthewmachuca/pen/poLLeGM" Style="{StaticResource WebviewStyle}" ></controls:WebView2>
    ```

## Using Webview2

For info using the Webview2 control: https://docs.microsoft.com/en-us/microsoft-edge/webview2/get-started/winui2