---
description: Informationen zur XP-Berechnung des Level-Systems
---

# XP-Berechnung

![](https://doc.pwr.lol/wp-content/uploads/2024/01/levelsystem\_userbanner.png)

Die PowerBot XP-Berechnung funktioniert wie folgt:

#### Senden von Nachrichten:

Beim Senden von Nachrichten bekommt man zufällig zwischen 6 und 25 XP pro Nachricht. Um Spam vorzubeugen gibt es einen Cooldown von 60 Sekunden. Wer dennoch spamt wird vom Auto-Mod verwarnt und getimeouted. Das Limit, ab wann es als Spam zählt, kann in den Auto-Mod Settings im Dashboard konfiguriert werden.

#### Verbringen von Minuten in Voice-Channels:

Im Dashboard können unter „Level-System“ Kategorien definiert werden, in denen man XP für das Verbringen in Voice-Channel bekommt. Sobald ein Member einen Voice-Channel der ausgewählten Kategorie betritt, fängt ein Timer an zu zählen. Wenn der Member diesen Voice-Channel wieder verlässt, wird der Timer gestoppt. Die verbrachten Minuten sind die XP, die der Member dann bekommt. Um XP-Farming vorzubeugen, gibt es eine maximale Anzahl an XP die man bekommen kann. In normalen Kategorien sind das 200XP (200 Minuten). In XP-Boost Kategorien sind es 400XP (200 Minuten). Verbringt ein User 500 Minuten durchgehend in einem Voice-Channel, so bekommt er trotzdem nur 200XP bzw. 400XP.

#### Berechnung LevelUp:

Die Berechnung für ein **Level-Up** funktioniert wie folgt: **Level \* Level \* 100 + 100** Möchte ich z.B. wissen wie viele XP benötige, damit ich auf Level 10 komme, dann muss ich folgendes rechnen: Lvl 9 \* Lvl 9 \* 100 + 100 = 8200 –> Man benötigt somit 8200XP damit man auf Level 10 kommt.

<table data-view="cards" data-full-width="true"><thead><tr><th>LEVEL</th><th>XP:</th></tr></thead><tbody><tr><td>0</td><td> 0</td></tr><tr><td>1</td><td>100</td></tr><tr><td>2</td><td>200</td></tr><tr><td>3</td><td>500</td></tr><tr><td>4</td><td>1000</td></tr><tr><td>5</td><td>1700</td></tr><tr><td>6</td><td>2600</td></tr><tr><td>7</td><td>3700</td></tr><tr><td>8</td><td>5000</td></tr><tr><td>9</td><td>6500</td></tr><tr><td>10</td><td>8200</td></tr><tr><td>11</td><td>10100</td></tr><tr><td>12</td><td>12200</td></tr><tr><td>13</td><td>14500</td></tr><tr><td>14</td><td>17000</td></tr><tr><td>15</td><td>19700</td></tr><tr><td>16</td><td>22600</td></tr><tr><td>17</td><td>25700</td></tr><tr><td>18</td><td>29000</td></tr><tr><td>19</td><td>32500</td></tr><tr><td>20</td><td>36200</td></tr><tr><td>21</td><td>40100</td></tr><tr><td>22</td><td>44200</td></tr><tr><td>23</td><td>48500</td></tr><tr><td>24</td><td>53000</td></tr><tr><td>25</td><td>57700</td></tr><tr><td>26</td><td>62600</td></tr><tr><td>27</td><td>67700</td></tr><tr><td>28</td><td>73000</td></tr><tr><td>29</td><td>78500</td></tr><tr><td>30</td><td>84200</td></tr><tr><td>31</td><td>90100</td></tr><tr><td>32</td><td>96200</td></tr><tr><td>33</td><td>102500</td></tr><tr><td>34</td><td>109000</td></tr><tr><td>35</td><td>115700</td></tr><tr><td>36</td><td>122600</td></tr><tr><td>37</td><td>129700</td></tr><tr><td>38</td><td>137000</td></tr><tr><td>39</td><td>144500</td></tr><tr><td>40</td><td>152200</td></tr><tr><td>41</td><td>160100</td></tr><tr><td>42</td><td>168200</td></tr><tr><td>43</td><td>176500</td></tr><tr><td>44</td><td>185000</td></tr><tr><td>45</td><td>193700</td></tr><tr><td>46</td><td>202600</td></tr><tr><td>47</td><td>211700</td></tr><tr><td>48</td><td>221000</td></tr><tr><td>49</td><td>230500</td></tr><tr><td>50</td><td>240200</td></tr><tr><td>51</td><td>250100</td></tr><tr><td>52</td><td>260200</td></tr><tr><td>53</td><td>270500</td></tr><tr><td>54</td><td>281000</td></tr><tr><td>55</td><td>291700</td></tr><tr><td>56</td><td>302600</td></tr><tr><td>57</td><td>313700</td></tr><tr><td>58</td><td>325000</td></tr><tr><td>59</td><td>336500</td></tr><tr><td>60</td><td>348200</td></tr><tr><td>61</td><td>360100</td></tr><tr><td>62</td><td>372200</td></tr><tr><td>63</td><td>384500</td></tr><tr><td>64</td><td>397000</td></tr><tr><td>65</td><td>409700</td></tr><tr><td>66</td><td>422600</td></tr><tr><td>67</td><td>435700</td></tr><tr><td>68</td><td>449000</td></tr><tr><td>69</td><td>462500</td></tr><tr><td>70</td><td>476200</td></tr><tr><td>71</td><td>490100</td></tr><tr><td>72</td><td>504200</td></tr><tr><td>73</td><td>518500</td></tr><tr><td>74</td><td>533000</td></tr><tr><td>75</td><td>547700</td></tr><tr><td>76</td><td>562600</td></tr><tr><td>77</td><td>577700</td></tr><tr><td>78</td><td>593000</td></tr><tr><td>79</td><td>608500</td></tr><tr><td>80</td><td>624200</td></tr><tr><td>81</td><td>640100</td></tr><tr><td>82</td><td>656200</td></tr><tr><td>83</td><td>672500</td></tr><tr><td>84</td><td>689000</td></tr><tr><td>85</td><td>705700</td></tr><tr><td>86</td><td>722600</td></tr><tr><td>87</td><td>739700</td></tr><tr><td>88</td><td>757000</td></tr><tr><td>89</td><td>774500</td></tr><tr><td>90</td><td>792200</td></tr><tr><td>91</td><td>810100</td></tr><tr><td>92</td><td>828200</td></tr><tr><td>93</td><td>846500</td></tr><tr><td>94</td><td>865000</td></tr><tr><td>95</td><td>883700</td></tr><tr><td>96</td><td>902600</td></tr><tr><td>97</td><td>921700</td></tr><tr><td>98</td><td>941000</td></tr><tr><td>99</td><td>960500</td></tr><tr><td>100</td><td>980200</td></tr></tbody></table>

&#x20;