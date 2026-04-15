<h1 align="center"><img src="gif/nickname.gif"></h1>
    
```cpp
class About : public Me
{
public:
    std::string_view _name    = "Vladislav";
    std::string_view _surname =  "Glushko";

    std::size_t _age = 24;
private:
    constexpr Like::Girl get_girl () const noexcept;
}

constexpr Like::Girl get_girl () const noexcept {
    return Like::Girl {
        "7FTrsE9tloO2lCG/uIkx0SORmkvUTilQ3SLHLAdz0r4=",
        "qwertypassword__", AES_MODE::ECB, "Base64", 128
    };
}
```    
___
<p align="center"><img src="https://komarev.com/ghpvc/?username=ISTECTION&label=PROFILE+VIEWS" alt="PROFILE VIEWS"></p>
