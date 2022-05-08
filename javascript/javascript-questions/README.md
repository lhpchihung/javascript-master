-   [1] Question 1 of 10

    ```javascript
    function whatDoesItDo(val) {
        return val ? 1 : 2;
    }
    ```

    A) It returns val
    B) It always return 1
    C) It always return 2
    D) It returns 1 if val is truthful, otherwwise 2

-   [2] Question 2 of 10

    ```javascript
    function whatDoesItDo(param) {
        return { blue: "#0000ff", green: "#00ff00", red: "#ff0000" }[param];
    }
    ```

    A) It returns an object with colors and an array with the value of param
    B) It converts red, green and blue colors to their hex values
    C) This is invalid JavaScript code

-   [3] Question 3 of 10

    ```javascript
    function whatDoesItDo(val) {
        if (color !== "blue" || color !== "green") {
            color = "red";
        }

        return color;
    }
    ```

    A) Always returns red
    B) Returns blue, green or red, depending on the parameter "color"
    C) Returns only blue and green

-   [4] Question 4 of 10

    ```javascript
    function whatDoesItDo(arr) {
        return arr.filter(function (elem, pos) {
            return arr.indexOf(elem) == pos;
        });
    }
    ```

    A) Sums all the elements in the array
    B) Always returns an empty array
    C) Removes duplicate values from an array

-   [5] Question 5 of 10

    ```javascript
    var f = function g() {
        return 23;
    };

    typeof g();
    ```

    A) Number
    B) Function
    C) Object
    D) Underfined

-   [6] Question 6 of 10

    ```javascript
    (function f(f) {
        return typeof f();
    })(function () {
        return 1;
    });
    ```

    A) Number
    B) Function
    C) Object
    D) Underfined

-   [7] Question 7 of 10

    ```javascript
    var foo = {
        bar: function () {
            return this.baz;
        },
        baz: 1,
    };

    (function () {
        return typeof arguments[0]();
    })(foo.baz);
    ```

    A) Number
    B) Function
    C) Object
    D) Underfined

-   [8] Question 8 of 10

    ```javascript
    (function(foo) {
        return typeof foo.bar;
    })({{ foo : { baz: 1 }})
    ```

    A) Number
    B) Function
    C) Object
    D) Underfined

-   [9] Question 9 of 10

    ```javascript
    (function f() {
        function f() {
            return 1;
        }
        return f();
        function f() {
            return 2;
        }
    })();
    ```

    A)
    B)
    C)
    D)

-   [10] Question 10 of 10

    ```javascript
    (function (x, f = () => x) {
        var x;
        var y = x;
        x = 2;

        return [x, y, f()];
    })(1);
    ```

    A) [2, 1, 1]
    B) [2, undefined, 1]
    C) [2, 1, 2]
    D) [2, undefined, 2]

    Answers:
    1: D
    2:
    3: A
    4: C
    5:
    6:
    7:
    8:
    9:
    10:

```

```
