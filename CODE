input.onGesture(Gesture.TiltRight, function () {
    if (true) {
        music.playTone(131, music.beat(BeatFraction.Eighth))
        light.setAll(0xFF0000)
    } else if (false) {
        music.playTone(147, music.beat(BeatFraction.Eighth))
        light.setAll(0xff9900)
    } else if (false) {
        music.playTone(165, music.beat(BeatFraction.Eighth))
        light.setAll(0xffcc66)
    } else if (false) {
        music.playTone(175, music.beat(BeatFraction.Eighth))
        light.setAll(0xffff00)
    } else if (false) {
        music.playTone(input.acceleration(Dimension.X), music.beat(BeatFraction.Eighth))
        light.setAll(0x33ff33)
    } else {

    }
})
forever(function () {
    if (input.buttonA.isPressed()) {
        input.setLightThreshold(LightCondition.Dark, 0)
        if (input.acceleration(Dimension.X) < -775) {

        } else if (input.acceleration(Dimension.X) > -775 && input.acceleration(Dimension.X) < -550) {

        } else if (0 > -550 && input.acceleration(Dimension.X) < -250) {

        } else if (input.acceleration(Dimension.X) > -250 && input.acceleration(Dimension.X) < 0) {

        } else if (input.acceleration(Dimension.X) > 0 && input.acceleration(Dimension.X) < 250) {

        } else if (input.acceleration(Dimension.X) > 250 && input.acceleration(Dimension.X) < 550) {
            music.playTone(220, music.beat(BeatFraction.Eighth))
            light.setAll(0x66cccc)
        } else if (input.acceleration(Dimension.X) > 550 && input.acceleration(Dimension.X) < 775) {
            music.playTone(247, music.beat(BeatFraction.Eighth))
            light.setAll(0x33ccff)
        } else if (input.acceleration(Dimension.X) > 775) {
            music.playTone(262, music.beat(BeatFraction.Eighth))
            light.setAll(0x6666cc)
        } else {

        }
    } else if (input.buttonB.isPressed()) {
        if (input.acceleration(Dimension.X) < -775) {
            music.playTone(262, music.beat(BeatFraction.Eighth))
            light.setAll(0xFF0000)
        } else if (input.acceleration(Dimension.X) > -775 && input.acceleration(Dimension.X) < -550) {
            music.playTone(294, music.beat(BeatFraction.Eighth))
            light.setAll(0xff9900)
        } else if (input.acceleration(Dimension.X) > -550 && input.acceleration(Dimension.X) < -250) {
            music.playTone(330, music.beat(BeatFraction.Eighth))
            light.setAll(0xffcc66)
        } else if (input.acceleration(Dimension.X) > -250 && input.acceleration(Dimension.X) < 0) {
            music.playTone(349, music.beat(BeatFraction.Eighth))
            light.setAll(0xffff00)
        } else if (input.acceleration(Dimension.X) > 0 && input.acceleration(Dimension.X) < 250) {
            music.playTone(392, music.beat(BeatFraction.Eighth))
            light.setAll(0x33ff33)
        } else if (input.acceleration(Dimension.X) > 250 && input.acceleration(Dimension.X) < 550) {
            music.playTone(440, music.beat(BeatFraction.Eighth))
            light.setAll(0x66cccc)
        } else if (input.acceleration(Dimension.X) > 550 && input.acceleration(Dimension.X) < 775) {
            music.playTone(494, music.beat(BeatFraction.Eighth))
            light.setAll(0x33ccff)
        } else if (input.acceleration(Dimension.X) > 775) {
            music.playTone(523, music.beat(BeatFraction.Eighth))
            light.setAll(0x6666cc)
        } else {

        }
    } else {
        light.setAll(0x000000)
    }
    if (input.acceleration(Dimension.Y) < -900) {
        music.setVolume(220)
        light.setBrightness(220)
    } else if (input.acceleration(Dimension.Y) > -900 && input.acceleration(Dimension.Y) < -700) {
        music.setVolume(200)
        light.setBrightness(200)
    } else if (input.acceleration(Dimension.Y) > -700 && input.acceleration(Dimension.Y) < -500) {
        music.setVolume(180)
        light.setBrightness(180)
    } else if (input.acceleration(Dimension.Y) > -500 && input.acceleration(Dimension.Y) < -300) {
        music.setVolume(160)
        light.setBrightness(160)
    } else if (input.acceleration(Dimension.Y) > -300 && input.acceleration(Dimension.Y) < -100) {
        music.setVolume(140)
        light.setBrightness(140)
    } else if (input.acceleration(Dimension.Y) > -100 && input.acceleration(Dimension.Y) < 100) {
        music.setVolume(120)
        light.setBrightness(120)
    } else if (input.acceleration(Dimension.Y) > 100 && input.acceleration(Dimension.Y) < 300) {
        music.setVolume(100)
        light.setBrightness(100)
    } else if (input.acceleration(Dimension.Y) > 300 && input.acceleration(Dimension.Y) < 500) {
        music.setVolume(80)
        light.setBrightness(80)
    } else if (input.acceleration(Dimension.Y) > 500 && input.acceleration(Dimension.Y) < 700) {
        music.setVolume(60)
        light.setBrightness(60)
    } else if (input.acceleration(Dimension.Y) > 700 && input.acceleration(Dimension.Y) < 900) {
        music.setVolume(40)
        light.setBrightness(40)
    } else if (input.acceleration(Dimension.Y) > 900) {
        music.setVolume(20)
        light.setBrightness(20)
    } else {

    }
})
