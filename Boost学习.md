### Boost学习

##### 1、数组Boost.Array

Header <boost/array.hpp>

```
namespace boost {
  template<typename T, std::size_t N> class array;
  template<typename T, std::size_t N> void swap(array<T, N>&, array<T, N>&);
  template<typename T, std::size_t N> 
    bool operator==(const array<T, N>&, const array<T, N>&);
  template<typename T, std::size_t N> 
    bool operator!=(const array<T, N>&, const array<T, N>&);
  template<typename T, std::size_t N> 
    bool operator<(const array<T, N>&, const array<T, N>&);
  template<typename T, std::size_t N> 
    bool operator>(const array<T, N>&, const array<T, N>&);
  template<typename T, std::size_t N> 
    bool operator<=(const array<T, N>&, const array<T, N>&);
  template<typename T, std::size_t N> 
    bool operator>=(const array<T, N>&, const array<T, N>&);
  template<typename T, std::size_t N, std::size_t Idx> 
    T boost::get(array<T, N>&);
  template<typename T, std::size_t N, std::size_t Idx> 
    T boost::get(const array<T, N>&);
}
```