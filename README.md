# DataHandler

Basic algorithms and data structures for data operations

## Common data structures

A common data structure used to store options and futures data is a map, also known as an associative array. A map allows you to store key-value pairs, where the key is a unique identifier (such as the option's ticker symbol) and the value is the option or future data.

Example:

std::map<std::string, OptionData> options;
options["AAPL"] = {123.45, 0.01, "CALL", "2022-07-01"};
options["GOOG"] = {678.90, 0.02, "PUT", "2023-03-01"};

In this example, we're using a map with string keys and OptionData values. The keys are the ticker symbols "AAPL" and "GOOG", and the values are the option data (strike price, volatility, type, expiration date).

Another data structure that could be used is a struct or a class. See `data.h`.
