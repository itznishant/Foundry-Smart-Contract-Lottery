<a name="readme-top"></a>

<!-- PROJECT INFO -->
<br />
<div>
  <h3 align="center">Project: Foundry Smart Contract Lottery </h3>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-project">About Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#requirements">Requirements</a></li>
      </ul>
    </li>
    <li><a href="#quickstart">Quickstart</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#testing">Testing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>


<!-- ABOUT -->
# About Project

## Foundry Smart Contract Lottery 

**Smart Contract Lottery**  is a Web3 project which consists of a Raffle smart contract built using  **Foundry** framework,  **Solidity** programming and leverages **Chainlink** decentralised oracle network.

The project is a part of Patrick Collins's (@PatrickAlphaC) Foundry Solidity course.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Built With

[![Solidity][soliditylang]][solidity-url]
[![Foundry][getfoundry]][foundry-url]
[![ChainLink][chain.link]][chainlink-url]
[![Alchemy][alchemy.com]][alchemy-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [foundry](https://getfoundry.sh/)
  - You'll know you did it right if you can run `forge --version` and you see a response like `forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z)`

## Quickstart

```
git clone https://github.com/itznishant/Foundry-Fund-Me/
cd Foundry-Fund-Me
forge build
```

## Usage

Deploy:

```
forge script scripts/DeployFundMe.s.sol
```


## Testing

This repo covers Unit, Forked & Integration tests. 


```
forge test
```

or 


To only run tests matching specified regex pattern, use:

```
forge test --mt testFunctionName 
```
or
```
forge test --match-test testFunctionName
```

### Test Coverage

```
forge coverage
```

## Contact

**Nishant Vemulakonda**

[![Twitter Follow itznish](https://img.shields.io/twitter/follow/itznish?style=for-the-badge&logo=twitter&logoColor=white&labelColor=1DA1F2&color=1DA1F2)](https://twitter.com/itznish)

[![Nishant Vemulakonda LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://in.linkedin.com/in/nishant-vemulakonda)

[![Nishant Vemulakonda GitHub followers](https://img.shields.io/github/followers/itznishant?label=GITHUB&style=for-the-badge&logo=github&logoColor=white&labelColor=black&color=blue)](https://github.com/itznishant/)

Linktree: [@nishant.social](https://linktr.ee/nishant.social)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Acknowledgments

* [Patrick Collins (@PatrickAlphaC)](https://www.youtube.com/@PatrickAlphaC)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[soliditylang]: https://img.shields.io/badge/SOLIDITY-black?style=for-the-badge&logo=solidity&logoColor=white
[solidity-url]: https://soliditylang.org/
[getfoundry]: https://img.shields.io/badge/FOUNDRY-gray?style=for-the-badge&logo=foundry&logoColor=white
[foundry-url]: https://getfoundry.sh/
[chain.link]: https://img.shields.io/badge/CHAINLINK-darkblue?style=for-the-badge&logo=chainlink&logoColor=white
[chainlink-url]: https://chain.link/
[alchemy.com]: https://img.shields.io/badge/alchemy-4b43e8?style=for-the-badge&logo=alchemy&logoColor=white
[alchemy-url]: https://www.alchemy.com/
