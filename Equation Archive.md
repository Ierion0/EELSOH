![](https://lh5.googleusercontent.com/cFxJIzWIw8aTH1H5QABUvFbuEqP0IKlSrdiGWDG2FS42lsSUbCkj0b8zn_E86gyZeE8fhqXUopi9rqO0RnEYaSsTl8N5SroTn4DiVRnlPQ0yhE8hS0UBJwEGm8597ABy9u6_IOqvk5gBTwRv6RNgVdKGpDPqyD5zMcc0Ir-PANsc0Qjw37-ECpyR9xr9CA)
This equation is an approximated growth curve of the chance of cancer over a 5 year period given Sv, base change for the sex at 20yo, and age.

![](https://lh6.googleusercontent.com/SftJAanXf4OnKnIHun9Rs2XSvuHzuA-bBC_WmCQxIR6ru30s8Ow2BE17nau5XqYIv9m5FCwPoEluOBQb5SdTrHIXwuhCHWVDoAzk-dFbWOljHBH914_RW93jsgbj4_k2TQ4ELgMUphCYdo_pZvdxCh2OgAklkLN8MzwqpWyvabBSc-cslMydrnJaxERjeA)
This is a curve that approximates the cancer rate until ~75-79 range, where the ‘top end’ of the growth curve would be. Then it follows the same approximate slope. `w` is how much the graph is slid over, and a more complex formula would have to be made to determine the weight, but it wouldn’t be hard to create. `f` is a random number meaning nothing. The square root is to represent the derivative that increases slowly, then levels off – which is what I believed made the most sense in this case and would fit the exponential part of the growth curve. The integral starts at 20 as the age estimates start at 20, and the ` - 205.2 ` is to start the curve at 0. The curve starting 20 f in is optimal, so I didn’t change that. The `.0..2` is just a coefficient, and constant 40 is the starting point for 20yo.

```
( 1-BARNS*10^(-10) ) ^ ( (g/m^3) * 10^(-27) *        N         / MOLARMASS )
\ %coverage of 1nm /   \ density /\ to nm^3 /\avagadro’s number/\ molar mass
```

