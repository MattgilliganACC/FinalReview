Consider the following code.  What would be console logged?  Why? (50%)

What would you change to address this issue (where the Apple type is
mis-represented in the last line below)? (50%)

    const apple = {
        type: 'Granny Smith',
        weight:  4
    }

    var orange = apple

    orange.type = 'Clementine'

    console.log('Apple type is ', apple.type)

The console will return "Apple type is Clementine." It overides Granny Smith as it comes later in the script.
This can be avoided by not choosing the same variable name as already exists.

