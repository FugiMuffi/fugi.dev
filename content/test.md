+++
title = "Test"
template = "generic.html"
+++

## This is a test
Hello!

```java
public Map<LocalDate, List<Deliverable>> getDeliverables() {
    return deliverables;
}
```

```hs
histogram :: [Int] -> [Int]
histogram xs = histogram' 1 xs
  where
    histogram' i xs = count i xs : histogram' (i+1) xs
    count _ [] = 0
    count i (x:xs)
      | i == x = 1 + count i xs
      | otherwise = count i xs
```

Code blocks work nicely!

Here's a quote:

> This is a quote.

[Back home](/)