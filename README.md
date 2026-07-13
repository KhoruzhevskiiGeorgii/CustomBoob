# CustomBoob — Interactive Formula Graph

An interactive browser visualization of

\[
x(y)=a y\ln(y)-\frac{b}{36}\exp\left[-\left(36y-\frac{c}{e}\right)^m\right].
\]

## Features

- adjustable parameters `a`, `b`, and `c`;
- `m` is restricted to positive even integers;
- only the part of the curve satisfying `x(y) < 0` is displayed;
- the coordinate scale is fixed so that one major grid square equals `1` unit on the x-axis and `0.5` units on the y-axis;
- an optional dense grid, disabled by default;
- synchronized zooming with the mouse wheel.

## Run locally

Open `index.html` in a modern browser. No build step or server is required.

## Publish with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the **main** branch and the **/(root)** folder.
5. Click **Save**.

The site will be published at:

`https://khoruzhevskiigeorgii.github.io/CustomBoob/`
