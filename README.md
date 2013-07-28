A simple tripleclick event for jQuery.

Click on an element three times within 1s to trigger the event.

Usage:

    $("#element").bind("tripleclick", function()
    {
        // Actions
    });

    // or

    $("#element").on("tripleclick", function()
    {
        // Actions
    });

You can also override the 1s time limit by passing in a new threshold,

    $("#element").on("tripleclick", { threshold: 2000 }, function()
    {
        // Actions
    });
