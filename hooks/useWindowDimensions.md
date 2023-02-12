# ScrollToTop

## Overview

This hook gives you the dimensions of the viewport.

## Required Packages

None.

## Guide

Just add the JS file to your project folder, import it to a component of your choice, and use it almost the same way you use useState hook.

    const [width, height] = useWindowDimensions();

The variables "width" and "height" represent the width and height of the viewport. They automatically change when the viewport dimensions change. Also, they can be any name you want.