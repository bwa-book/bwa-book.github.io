---
layout: article
title: Errata
permalink: /errata/
---

The following errors snuck into the published book:

### Chapter 6

- p79: In the method definition `updateButtonToStopped`, the `UIColor` initialisation should read as follows:

    ```
    let goColor = UIColor.init(red:4/255, green:222/255, blue:13/255, alpha:0.28)
    ```

    In the method definition `updateButtonToGoing`, the `UIColor` initialisation should read as follows:

    ```
    let stopColor = UIColor.init(red:250/255, green:17/255, blue:79/255, alpha:0.34)
    ```

### Chapter 12

- p196: In step 2, after adding `poster.png` to the asset catalog, select the Watch options in its Attributes Inspector.

### Chapter 14

- p236: The method definition `updateLabel` is missing a closing parenthesis and should read as follows:

    ```
    private func updateLabel() {
        label.setText(String(maxCadence))
    }
    ```
