# compare-domain-list
how to Compare two different files line by line. In this particular case would be, comparing 2 files with a list of domains that you might need to compare to check the common lines and the differences between these 2 txt files


# Instead of importing diff module, I'd use a while loop just to make it more user friendly.

****** Approach*******

- Open both files in read mode
- Store list of strings
- Compare both .txt files with the help of intersection() method for common strings
- Compare both files for differences using while loop
- Close both files
- Print similarities and differents lines as output
