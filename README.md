# Go Lang

Tutorial by [Programming Zaman Now](https://www.youtube.com/playlist?list=PL-CtdCApEFH_t5_dtCQZgWJqWF45WRgZw)

<!-- ? Session 2 -->
  <details>
  <summary>
    <h2 style="display: inline-block; margin-bottom: 8px;">Session 2 - Build & Run</h2>
  </summary>

- **Build** (Usually for production)
  ```go
  go build [path/file_go]
  // It will create executeable program compatible to any OS
  ```
- **Run** (Usually for development)
  ```go
  go run [path/file_go]
  // execute directly
  ```
  </details>

<details>
  <summary>
    <h2 style="display: inline-block; margin-bottom: 8px;">Session 3 - Data Type Number</h2>
  </summary>

### Number

| Data Type  | Min Value            | Max Value            |
| ---------- | -------------------- | -------------------- |
| **int8**   | -128                 | 127                  |
| **int16**  | -32768               | 32767                |
| **int32**  | -2147483648          | 2147483647           |
| **int64**  | -9223372036854775808 | 9223372036854775807  |
| **uint8**  | 0                    | 255                  |
| **uint16** | 0                    | 655535               |
| **uint32** | 0                    | 4294967295           |
| **uint64** | 0                    | 18446744073709551615 |

### Floating Point

  <table>
    <thead>
      <tr>
        <th>Data Type</th>
        <th>Min Value</th>
        <th>Max Value</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>float32</b></td>
        <td>1.18x10<sup>-38</sup></td>
        <td>3.4x10<sup>38</sup></td>
      </tr>
      <tr>
        <td><b>float64</b></td>
        <td>2.23x10<sup>-308</sup></td>
        <td>1.80x10<sup>308</sup></td>
      </tr>
      <tr>
        <td><b>complex64</b></td>
        <td colspan=2>complex numbers with float32 and imaginary parts.</td>
      </tr>
      <tr>
        <td><b>complex128</b></td>
        <td colspan=2>complex numbers with float64 and imaginary parts.</td>
      </tr>
    </tbody>
  </table>

### Alias

| Data Type | Alias For  |
| --------- | ---------- |
| byte      | uint8      |
| rune      | int32      |
| int       | min int32  |
| uint      | min uint32 |

### Example

```go
package main

import "fmt"

func main(){
fmt.Println("Satu = ", 1)
fmt.Println("Dua = ", 2)
fmt.Println("Tiga Koma Lima = ", 3.5)
}
```

  </summary>

</details>
