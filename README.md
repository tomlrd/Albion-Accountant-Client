# Albion Accountant

Auction house accounting for Albion Online. It keeps the books for what you sell:
every sale with its real price, its tax, what it actually brought in, and what is
still waiting on the market.

## Install

Download the installer from the [latest release](https://github.com/tomlrd/Albion-Accountant-Client/releases/latest)
and run it. Nothing else is needed.

The app has no window of its own. It sits in the tray and opens its pages in your
browser; a left click on the tray icon brings them back.

**It needs administrator rights** to read the game's traffic, and asks for them at
startup. It reads, it never sends anything to the game.

## Sessions

![The sessions page](screen1.png)

A session is one run of trading. Open the auction house in game and your sales land
in the session you have open; close it when the run is over and open a new one for
the next.

Each sale is a card carrying what it is worth: unit price, gross, sales tax, setup
fee, and the net that actually reached your purse. A sell order also shows how much
of it has gone, what it will be worth once the rest sells, and how long it stays
listed. Every sale keeps the market it was made in, so a session that toured three
cities says so and each one can be renamed.

The session line above the cards is the whole run at a glance: what it will be worth
once every order sells, what you are already holding, and what each player gets. Set
your own cut in `% your tax` and it is deducted everywhere.

Choose which columns a card shows, sort the cards and the sessions, fold a session
down to its title, or drag a sale into another session. The `copy` button on a
session writes it as a message ready to paste into a channel.

## Charts

![The charts page](screen2.png)

The same figures over time, from the last hour to the last year, and filtered to one
market or one seller.

Pick a measure — net, pending, gross, fees, sales tax, setup fee, repairs, quantity,
operations, unit price, competitors — and it is drawn per period and as a running
total. Below, every measure at once on a single scaled chart, so you can see them
move against each other.

The heatmap answers the question a timeline cannot: which hours and which days are
actually worth selling on. The table at the bottom breaks the range down by item,
type, tier, quality, enchantment, buyer, seller or market.

## Settings

![The settings page](screen3.png)

Tell it whether you have premium, since that is what sets your sales tax. Turn on
repair costs to have them counted against a session. Create a desktop shortcut that
starts the game and the app together, and choose whether the pages open by
themselves.

`someone else's session` takes a session shared from another machine and adds it to
your list, exactly as it was counted there — nothing is recomputed with your rates.

The Discord message is yours to write, with a live preview beside the editor and a
list of the values you can drop into it.

## Updates

The app checks for a new version when it starts and offers to install it. Your
sessions and your history are never touched by an update.

## Releases

This repository carries the releases. Every one of them lists what changed.
