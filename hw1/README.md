## CLI 命令行实用程序开发基础
#### 测试
go run selpg -s1 -e1 testfile.txt
![-s1 -e1 testfile.txt][1]
![-s1 -e1 testfile.txt][2]

go run selpg -s1 -e1 < testfile.txt
![-s1 -e1 testfile.txt][3]
![-s1 -e1 testfile.txt][4]

dir | go run selpg -s1 -e2
![-s1 -e1 testfile.txt][5]

go run selpg -s10 -e20 testfile.txt >out.txt
![-s1 -e1 testfile.txt][6]
![-s1 -e1 testfile.txt][7]

go run selpg -s10 -e20 testfile.txt 2>err.txt
![-s1 -e1 testfile.txt][8]
![-s1 -e1 testfile.txt][9]

go run selpg -s10 -e20 testfile.txt >out.txt 2>err.txt
![ ][10]
![ ][11]
![ ][12]

go run selpg -s10 -e20 testfile.txt >out.txt 2>nul
![ ][13]
![ ][14]

go run selpg -s10 -e20 testfile.txt >nul
![ ][15]



  [1]: https://img3.doubanio.com/view/status/m/public/ff8a8bb8e375b7f.webp
  [2]: https://img3.doubanio.com/view/status/m/public/0a12c687014dcc1.webp
  [3]: https://img1.doubanio.com/view/status/m/public/a3dfe805de194a9.webp
  [4]: https://img1.doubanio.com/view/status/m/public/d6d82ac6df1ee8b.webp
  [5]: https://img1.doubanio.com/view/status/m/public/ec6da20af403efc.webp
  [6]: https://img3.doubanio.com/view/status/m/public/cd9b57d5e0886d0.webp
  [7]: https://img3.doubanio.com/view/status/m/public/f1f1191ab63a8d1.webp
  [8]: https://img3.doubanio.com/view/status/m/public/dc124b4a0f0b965.webp
  [9]: https://img1.doubanio.com/view/status/m/public/75b59f1e6fbeb98.webp
  [10]: https://img1.doubanio.com/view/status/m/public/c28a2bfc97c5a28.webp
  [11]: https://img3.doubanio.com/view/status/m/public/2a2038fd1f57212.webp
  [12]: https://img1.doubanio.com/view/status/m/public/446aecbaea4813a.webp
  [13]: https://img3.doubanio.com/view/status/m/public/86b8796b716d514.webp
  [14]: https://img1.doubanio.com/view/status/m/public/062814e8d4d8bfc.webp
  [15]:https://img3.doubanio.com/view/status/m/public/e7b1aadbeeaa55e.webp