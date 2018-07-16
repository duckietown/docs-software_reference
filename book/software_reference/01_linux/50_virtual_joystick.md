# Virtual Joystick {#virjoy status=draft}

Assigned: Julien Kindle

The virtual joystick allows users to steer a Duckiebot by using the arrow keys on a keyboard. This is very useful in situations where either no hardware joystick is present or many people steer Duckiebots.


## Installation

While in duckietown_root folder, check out the branch megacity on your laptop

    laptop $ git checkout megacity
    laptop $ git pull

and install pygame

    laptop $ pip install pygame

## Usage

Launch any demo on your Duckiebot, for example

    duckiebot $ make demo-joystick

Then, start the virtual joystick on your laptop

    laptop $ make virjoy-<vehicle_name>

## Commands

<col2 class='command-table labels-row1' figure-id="tab:keys-virjoy" figure-caption="Key mappings">
    <s>Keys</s>
    <s>Function</s>

    <s><kbd>↑↓←→</kbd></s>
    <s>Steer your Duckiebot</s>

    <s><kbd>q</kbd></s>
    <s>Quit the program</s>

    <s><kbd>a</kbd></s>
    <s>Turn on line-following a.k.a. autopilot</s>

    <s><kbd>s</kbd></s>
    <s>Stop line-following</s>

    <s><kbd>i</kbd></s>
    <s>Toggle anti-instagram</s>

</col2>



<style>
.command-table td {
    text-align: left;
    font-size: 80%;
}
</style>
