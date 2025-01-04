# SD-whitepaper

Early designs and ideas for the stop dropper tool.

<br/>

## Why?

I made this tool for myself becuase I realized that I would spend a ton of time using my broker's clunky tools.

The purpose of this tool was to make creating and adjusting __my own___ stop orders super fast and easy, and I'm excited to share this platform for others to use as well.

<br/>

## How?

This platform exposes a unique and expressive control system that allows you to modify a set of stop orders in just a few easy clicks.

But before we get into all that, let's define some terms.

<br>

## A "Stop Ladder" Example

Let's suppose we are trading SPY, and we have three shares.

We can create a series of stop market sell orders with stop prices below the current price, and our broker's servers will be automatically watching for you and will trigger the market sell order if the price of SPY drops down to there.

<img src="./placeholder.jpg"/>

<br/>

## Why Are Stop Ladders Useful?

Setting stop limit orders is a risk management strategy that protects you against large losses.

The idea is that as your profit goes down, the size of your position goes down, and therefore your overall risk goes down.

This technique allows traders to have peace of mind with a "worst case maximum loss" much lower than the full investment.

You're betting on a direction, and if you're wrong then these stop order will automatically cut your losses and you can just move on without having to make any difficult, emotional decisions later on when you're down.

<br/>

## Dollar Cost Averaging _Out_ of a Postion

<br/>

## It Works For Shorting Too! 


<br/>

## Buffer, Gaps, and Weights

Let's define some terms now: ___buffer___, ___gaps___, and ___weights___.

We'll use the term ___buffer___ to define the distance between the underlying current price and the trigger price of the stop order that closest the the underlying price (ie. first stop to be triggered). This can be expressed either as a percentage of the underlying or as an exactly dollar and cents amount.

Let's call a ___gap___ the distance between two stops. The gaps in a ladder can all be the same size or they can be defined by a generic "gap distance algorithm".

Let's use the term ___weights___ to refer to how many shares are sold when each stop order is triggered. This too can be defined by a generic "stop weights algorithm".

Here is the image from above annotated to show the buffer, gaps, and weights:

<img src="./placeholder.jpg"/>

<br>

## Adjusting Your Stops

Going in an adjusting your stops manually can be extremely tedious, and we made this platform exactly so you don't have to!

If the underlying moves in your favor then the buffer becomes very large.

At this point you may want to "lock in gains" by moving the trigger price of one or move stops close to the underlying.

There are a few different ways you could modify your stop ladder.


1)








