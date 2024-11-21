
input.onGesture(Gesture.Shake,function () =>  {
    basic.clearScreen()
    let randomNumber = randint(0, 4)
    if (randomNumber == 3) {
        basic.showString("Do it Again")
    } else if (randomNumber == 2) {
        basic.showString("YEAH")
    } else if (randomNumber == 1) {
        basic.showString("NOPE")
    } else {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(8)
})
let randomNumber = 0
basic.showString("ASK A QUESTION")
basic.showNumber(8)


