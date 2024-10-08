# Lazy iterators
In this assignment we worked towards modifying the polygons sequence type into an iterable. <br/>
Rather than using a list to iterator over, as we did in the [previous assignment (class notebook)](https://github.com/DimpleB0501/epai5_iterable_iterators_part1/blob/main/iterators_iterables.ipynb) and its corresponding python [Polygons Iterator Class](https://github.com/DimpleB0501/epai5_iterable_iterators_part1/blob/main/iterators_iterables.ipynb) code. <br/>
In this assignment we implemented a lazy iterator (using Polygon class rather than a list). The advantage of directly using the Polygon class is calculations/ processing is invoked only when the class is called.

### Results
![op](lazy_iterator.png)

### Codes
[ipython notebook](https://github.com/DimpleB0501/epai_s11_lazy_iterators/blob/main/iterables_iterators_part2.ipynb), main code, <br/>
[polygon](https://github.com/DimpleB0501/epai_s11_lazy_iterators/blob/main/polygon.py), properties of the polygon class are calculated here, <br/>
[polygons](https://github.com/DimpleB0501/epai_s11_lazy_iterators/blob/main/polygons.py), lazy iterator and a polygons sequence is implemented here.
