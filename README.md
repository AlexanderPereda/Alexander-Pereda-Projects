# [Alexander Pereda Portfolio](https://alexanderpereda.github.io/)
Summary of the data science projects that we have been working on.

## [Project 1 : CLASSIFICATION OF CELL PHONES ACCORDING TO PRICE](https://github.com/AlexanderPereda/Alexander-Pereda-Projects/blob/main/Cell%20phone%20price%20ranking%20with%20SVM.ipynb)

* A multiple classification algorithm was created to rank the different cell phone prices in 4 categories.
* EDA was performed on the dataset looking for which variables have the greatest impact on the classification.
* We train a basic model and then optimize it step by step to see how the right choice of parameters can influence the final algorithm.
* We use EDA, GridSearchCV and  Support Vector Classifier to obtain the best model.


    ![](https://github.com/AlexanderPereda/AlexanderPereda.github.io/blob/main/images/phones.jpg)



## [Project 2 : DIMENSIONALITY REDUCTION USING PCA](https://github.com/AlexanderPereda/Alexander-Pereda-Projects/blob/main/Dimensionality%20reduction%20using%20PCA.ipynb)

* d

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA3gAAAJcCAYAAACrJAbaAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nOzdd5iU1dmA8fsRUKQIKIqNZsOKJbZojEAsxB4TS4I1UUzsidGYYOxoEo01JoqJHbvB3gXsvcZGbIAFjSCigCLlfH+c2W+HZRcW3NnZnb1/1zXXznveMs+cmd2dZ06LlBKSJEmSpOZvsXIHIEmSJElqGCZ4kiRJklQhTPAkSZIkqUKY4EmSJElShTDBkyRJkqQKYYInSZIkSRXCBE+SKlBE9IqIFBGtyx2L1BRExNiI2KZw/w8R8c9SPoYklYsJnqQWq/Bh7H8R0b6o7KCIGF3GsFRGEXFyRFzTwNdsGxGfR8SAWvadGxE3F+6PjYivImJq0e1vhX0HRMTsQtkXEfFyROxU41q/iIg3I+LLiPgkIu6OiI6FfaMj4qAax/eLiA+KtneNiJcK158YESMjonctMR8fEY/UUt41Ir6JiHW/RV1VfTExtcZtr0W9Zm1SSmeklA5a8JGS1PyY4Elq6VoBR5U7iJpseascKaWvgRuA/YrLI6IV8FPgyqLinVNKHYpuhxftezKl1AHoDPwduD4iOheutTVwBvDTlFJHYK3CY9ZLRKwGXAUcA3QCegMXAbNrOfwaYItakr+9gf+klF5diMeNiKjts0jnGvVQ7+ciSS2dCZ6klu4s4LdVH5SL1dbNsbglpNCq8nihFebziHg3IrYolL9faB3cv+jcJSLi7IgYX2hhuTgilizs6xcRH0TE7yLiY+DywvHnRcRHhdt5EbFEbU8iIloVrj0xIt4Fdqyxv1NE/CsiJkTEhxFxeiHBqOtaf4iIdwqtQc9HRPfCvi0i4tmImFL4uUWNujk9Ip4otLrcERHLRMTwQqvQsxHRq+j4FBFHFuptYkScVfVhPyIWi4gTImJcoR6viohONV6X/Qt1OTEihhRdd7FCK9M7ETEpIm6MiKUXdG5EDAT+AOxViP/lBdVdRKwWEQ8X6mNiRNSViFwJ/Dgi2hWVbU/+P3xPHefUKqU0B7gaaA+sXijehJwAvlg45rOU0pUppS/redkNgPdSSg+l7MuU0i0ppfG1PP4HwEhg3xq79gOuioguEXFnRHwaEZML91euOqjwPhkaEY8D04FV6hNgRCweuYXxiMJ2q8Lv34mF7ZMj4uaIuKHwvn0hItav41pztdRGxPcK79vPC7+7BxTKd4yIFwvv3/cj4uQa19m38B6dVPweLOzbNCKeLFxzQkT8LSIWr89zlaRvwwRPUkv3HDAa+O0inr8Z8AqwDHAtcD35w/ZqwD7A3yKiQ+HYPwFrkD9MrwasBJxYdK3lgaWBnsBgYAiweeH49YFNgRPqiONgYCdgQ2Bj4Cc19l8BzCo87obAdkBdXdR+Q25Z2gFYCvg5ML2QJN0FXFB4vucAd0XEMkXn7k3+4L8SsCrwJHB54Xm9AZxU47F+VIh3I2DXwmMBHFC49ScnAB2Av9U493tAH+AHwIkRsVah/AhgN2BrYEVgMrk1ar7nppTuJbeC3VBoNapKDq6g7ro7Dbgf6AKsDFxILVJKTwATgN2LivcFrk0pzartnLoUkssDgZnAuELx08D2EXFKRGwZdXwRMB8vAGtG/rKif9F7ti5XUpTgRUQf8vv0WvJni8vJ7+MewFfM+9rtS36Pdyx6DvOVUvqG/Dt1auG1Pp7cAj+06LBdgZvI77drgVsjos38rhsRPclJ9oXAsoXn8VJh9zRy4tqZ/KXJryJit8J5awP/KDyXFcm/EysXXXo28GugK/Bd8nvt0Po8V0n6VlJK3rx589Yib8BYYBtgXWAK+cPdQcDowv5eQAJaF50zGjiocP8A4K2ifesVju9WVDaJ/IExyB8WVy3a911yqwlAP+AboG3R/neAHYq2twfG1vFcRgK/LNrerip2oBswA1iyaP9PgVF1XGsMsGst5fsCz9QoexI4oKhuhhTt+ytwT9H2zsBLRdsJGFi0fSjwUOH+Q8ChRfv6kBOa1kWvy8pF+58B9i7cfwP4QdG+FRbi3JOBa4r2zbfuyN0ahxVfbz7vtxOA+wv3lyK3Xm1Y4/04Ffi86HZw0XttVqFsJjlp2rPG9X8I3FE4Zio5AW9V831bdHw/4IOi7c2BG4FPga/JiW2HOp5LO+ALYIvC9lDgtjqO3QCYXON36NQ6jq16fT6vcVur6JhjyO/RycDqReUnA08VbS9GTqq3Kv59r/k6A78HRtTzb8Z5wLmF+ycC1xfta0/+Hd6mjnOPru/jePPmzdu3udmCJ6nFS3nM0J3kFoGF9UnR/a8K16tZ1oGcPLYDni902focuLdQXuXTlMdrVVmRuVs3xhXKarMi8H6NY6v0BNoAE4oe+xJguTqu1Z2cXNb2GDVbW8aRW+uq1HzutdVFsZoxVz2/2p57VbJa5eOi+9OLrt0TGFH0XN8gt6bU59yaFlR3x5GT92ci4rWI+Hkd14HcrbJ/RKxIbmF9JxW6VBbZLaXUueh2adG+p1JKncmthbcDWxWfmFK6J6W0M7n1aldyUljV0jir8DyKtSEni1XnP5VS2jOltGzh2t8ntyLPI6U0ndxStl9EBDCInOwSEe0i4pJC18UvgEeAzjF3l+D357no3LrWqIc3ivZdSX5d7k4pvVXjvP+/bspdWT+g7t+ZKnW934mIzSJiVKG76RTgl+QWOajxO5dSmkb+Qqfq3DUK3VM/LtTDGUXnSlLJmOBJUnYSuZtjcbIyrfCzeNzU8ot4/YnkBGedog+tnVKeNKNKqnHOR+QPslV6FMpqM4H8QbX42Crvk1uhij80L5VSWqeOa71P7l5ZU814qh7nwzquUx81Y656frU991nMnTDW5X3ghzUShLYppfrEWfM1mG/dpZQ+TikdnFJaETgE+HvkCUvmvXBK44BHyd0M92XuyVXqLaU0FfgVsG9EbFjL/jkppYfIrbpVM1qOJ7eOFetNHd0jU0rPAv8uOr82VwJ7AtuSu1reUSg/htziullKaSlyogg5Ef7/h5jPdRfk7+QvZLaPiO/V2Pf/76fI4zlXpu7fmSp1vd8hd/O8HeieUuoEXEz185jrd64wvrK4u/I/gDfJrYxLkcd3FteBJJWECZ4kASmlt8mzDh5ZVPYpOXnZpzChw8+p+4Pggq4/B7gUODcilgOIiJUiYvv5nHYdcEJELBsRXcldwuqawv9G4MiIWDkiulDUGplSmkAeJ/bXiFgq8iQkq0aeebE2/wROi4jVI+tbGGd3N7BGRPwsIlpHnrp+bfKH7UV1bGFSju7k2UyrJim5Dvh1RPQujAerGhtXn/FqFwNDC2OrKNTfrvWM5xOgVyE5WGDdRcQeUT2ByGRy4jJnPte/Ejgc2BIYXs+Y5pFS+oz8OlVNMLJrROxdqMuIiE3JYxCfKpxyA3BgYeKPiIg1yOPDri+c/72IOLjovbkmsEvR+bV5lNx9chi5q+I3hfKO5C8zPi+M26w57nKRRcS+wHfIrZNHAlfWGC/4nYjYPfLESEeTk/P5PQfIr8M2EbFn4X29TERsUPRcPkspfV2o058VnXczsFOh7hYHTmXuz1Udyd1Ypxbq81eL8pwlaWGZ4ElStVPJ42iKHQwcS+56tQ7wxLe4/u+At4GnCl22HiS3dNTldPIkMK8A/yFPhHF6HcdeCtwHvFw47t819u8HLA68Tk5EbiaPTavNOeSE8X7yB9R/kcegTSJP5HIMuT6OA3ZKKU2cz3NYkNuA58mTWtxVeCyAy8hdGh8B3iOPCTuintc8n9zqcn9EfEn+gL9ZPc+9qfBzUkS8ULg/v7rbBHg6IqYWHvOolNK787n+LeQulA8Vksea7oi5138bMZ9rnQfsEBF9C3EdDLxFfs2uAc5KKQ0HSCndR076LyePN72bnGwOK1zrc3JC95/Cc7kXGAH8pa4HTyklcrfMnoWfxXEtSW61fqpwrTpFxD0R8YcaxZ/XqIffRESPwrX3SylNTSldS/79OLfovNuAvQr1sS+we0ppJvOR8kyhO5Df15+R34tVE+wcSp7U5UtyMn1j0XmvAYeRW/kmFB7zg+or81tyQvgl+ffTpR4kNYrIf58lSWpcEZHI3dfeLncsav4iL2GwWkppn3LHIknlZAueJEmSJFUIEzxJkiRJqhB20ZQkSZKkCmELniRJkiRViNblDmBhde7cOa22Wq1LDLU406ZNo337mhP+tTzWQzXropp1Uc26yKyHatZFNesisx6qWRfVrIum6/nnn5+YUlq2tn3NLsHr1q0bzz33XLnDaBJGjx5Nv379yh1G2VkP1ayLatZFNesisx6qWRfVrIvMeqhmXVSzLpquiBhX1z67aEqSJElShTDBkyRJkqQKYYInSZIkSRXCBE+SJEmSKoQJniRJkiRVCBM8SZIkSaoQJniSJEmSVCFM8CRJkiSpQpjgSZIkSVKFMMGTJEmSpAphgidJkiRJFcIET5IkSZIqhAmeJEmSJFUIEzxJkiRJqhAmeJIkSZJUIUzwJEmSJKlCmOBJkiRJUoUwwZMkSZKkCmGCJ0mSJEkVwgRPkiRJkiqECZ4kSZIkVQgTPEmSJEmqECZ4kiRJklQhTPAkSZIkqUKY4EmSJElShTDBkyRJkqQKYYInSZIkSRXCBE+SJEmSKoQJniRJkiRVCBM8SZIkSaoQJniSJEmSVCFM8CRJkiSpQpjgSZIkSVKFMMGTJEmSpAphgidJkiRJFcIET5IkSZIqhAmeJEmSJFUIEzxJkiRJqhAmeJIkSZJUIUzwJEmSJKlCmOBJkiRJUoUwwZMkSZKkCmGCJ0mSJEkVwgRPkiRJkiqECZ4kSZIkVYiSJXgRcVlE/C8iXq1jf0TEBRHxdkS8EhEblSoWSZIkSVoYw4dDr16w2GL55/Dh5Y6ofkrZgncFMHA++38IrF64DQb+UcJYJEmSJKlerr4aDj4Yxo2DlPLPwYObR5LXulQXTik9EhG95nPIrsBVKaUEPBURnSNihZTShFLFJEmSJKkyzJkD06fDtGn51q0btG8PH38MTz+dy6ZOrd6///7QvTs88ghcdFF1edVxt94Ka6wBf/sbHHHEvI83fToMGQKDBjX+c10YJUvw6mEl4P2i7Q8KZfMkeBExmNzKR7du3RolOEmSJKklGj48JzLjx29Njx4wdOiiJzVz5sBXX+Ukqm1bWGqpnCg9+eTcyde0adC/P6y/fm4tO/XUuZOvadNy2cCBOUEbODBft9idd8KOO8Izz8Buu80by/e+lxO8yZPhpZegQ4ecEC6zDPToAa0LmdGmm9b9fMaPX7R6aEzlTPDqLaU0DBgG0KdPn1TmcCRJkqSKNHx47oo4fTpAMG4c/PznMHo07LcfbLUVzJwJxx47bwK29965W+PEibD22rksXyc780w4/niYMAG22Wbex77ggpzgTZsG995bnYC1bw9LLw1t2uTjuneHww6r3ld1XN++ef/3vw8vvFC9v+pWdf6uu+ZbXTbdFHr2zIlmTT16LEKlNrJyJngfAt2LtlculEmSJElqJCnBa6/BlCm55a44KQP45hv45z+hVauc4LVqBZdfPm8CNWdOPr59e9h993kTsC22yPtXWgkefnje8zt2zPvXXhs+nE9W0Ls3nHVW3fs7d4YNN1z0+oDcalmd6Gbt2uXypq6cCd7twOERcT2wGTDF8XeSJElS6b31Fjz0EIwcmVvnPv0UNtmk7i6IEdVJ1WKL5WSwLksuCRdfXPf+tm1zK1tTVtUlNXdV5Vt3VW1MJUvwIuI6oB/QNSI+AE4C2gCklC4G7gZ2AN4GpgMHlioWSZIkqaVKCd57D559FvbaK5cdd1yeVGTllfN4tv79861fv7q7Jla1sLUUgwY1j4SuplLOovnTBexPwGGlenxJkiSppfrkE7jvPhg1KrfSVbXMff/7sMIKcNpp8Je/wGqr5da5Ks25a6KyUq6DJ0mSJKkRfPwxXHdd9di1e+7JywLcfnvuevm3v+Vxdssvn/evuy6svvrcyR3kFqthw/IkIxGJnj3zdnNsyWqpmsUsmpIkSZKqTZ8Od9+dW+hGjYI33sjll1ySW+B22SUvBbDeennM3MKo6po4evTD9OvXr8FjV2mZ4EmSJElN3Oef5/XfOnbMY+WmT4c99sizT261FRx4YC6vmj1y6aXzTS2PCZ4kSZLUBD3wQL6NGpXXdZszJ7fM9e8PXbvmsnXXrV7fTQITPEmSJKnspk+HJ56Ad96BQw7JZaecAs88A5tvDn/8Y07sNt+8+pxvu9abKpMJniRJklQGr7wCI0bkWS6feiovKN6uHRxwACyxBFx1VZ4UpV27ckeq5sRZNCVJkqQSmzkTnnwSzjgDPvssl917b26lmzYNjjwS7rorz4a5xBJ5/yqrmNxp4dmCJ0mSJJXAJ5/kVrhRo+DRR2Hq1Fy+8caw3XZw8MH51qVLeeNUZTHBkyRJkr6lOXPg1Vdzd8v118/j5SZPhuOOgzXXhP32y2Vbbw3LLpvPMbFTKZjgSZIkSYtgzhy4+OKc1I0eDZMm5fJjjsnJXJ8+8NFHsMIKZQ1TLYwJniRJkrQAKeUZLkeNymPmjj46LyB+3nkwYwbstBMMGJATu+7d8zkRJndqfCZ4kiRJavGGD4chQ2D8+K3p0QOGDoVBg/LEJzfemFvpPvggH7vuujnBA3j6aejcOSdzUlNggidJkqQWbfhwGDw4r0UHwbhxeRvgxRfh7rtzy1zVrU+f6nMdR6emxgRPkiRJLVZKecxcTu6qTZ+eW/Reew3+8pfcHVNqDkzwJEmS1GI9/nhezqA248dD+/aNG4/0bfldhCRJklqElOCJJ/KSBccfn8u23BK6dq39+B49Gi82qaGY4EmSJKmiTZkCF12U16fbcku49dbqSVEi8kyY7drNfU67dnmiFam5McGTJElSRTvuODj8cGjTBoYNy2vTnXlm9f5Bg3J5z54QkejZM28PGlS+mKVFZYInSZKkijF1Klx6KWy8MTz3XC777W/h2Wfh+efh4IOhQ4d5zxs0CMaOhZEjH2bsWJM7NV9OsiJJkqRm7+WX4ZJL4Jpr4Msv81p1X3yR962+enljkxqTCZ4kSZKapZTyGLqvv4att84/99oLDjkEvvtdFx9Xy2SCJ0mSpGbljTdya91zz8Gjj0LbtjBiRJ5EZemlyx2dVF6OwZMkSVKTN2MGXHttbqlbe234+9+he/c85g6gf3+TOwlswZMkSVITVtUN87bb8sQnq64Kf/4zHHAALLdcuaOTmh4TPEmSJDUpM2fmhO6SS2DAAPj972G33eD+++EHP4DF7IMm1clfD0mSJDUJY8fCkCHQowfssQeMGQNduuR9iy8O225rcictiC14kiRJKps5c6qTtsMPh3vugR13zDNhDhwIrVqVNz6pufE7EEmSJDW6Dz+EU06B3r1zyx3AWWfBe+/B7bfnJM/kTlp4tuBJkiSpUcyZk8fRXXwx3HknzJ4N229fPRPmWmuVNz6pEpjgSZIkqaRmz86tcRMnwi67QOfOcOyxcPDBsMoq5Y5OqiwmeJIkSWpwc+bAqFF5JszJk+GBB/KyBqNGwSab5ElTJDU8x+BJkiSpwUycCGefDWuuCdtsAw89BOuvn1vxALbc0uROKiUTPEmSJH0rKVUncNdem7tfLrccXH11nkzl7LOdMEVqLCZ4kiRJWiSTJ8MFF8A668AVV+Sy/feH//wHHnsM9tkH2rYta4hSi+MYPEmSJC2Up5/OM2HecAN89RVsuil065b3deqUb5LKwwRPkiRJCzRzJrRpk+8ffji8+Sbst19ekHzDDcsbm6RqJniSJEmq0wsv5JkwR4yAMWOgS5c8tm6llaBjx3JHJ6kmEzxJkiTNZfp0uP763A3z2WdhySVh771zeZcueYZMSU2Tk6xIkiS1UMOHQ69eMGDA1vTqBVdemcvHj4df/AKmTcuTqHz0EVx2WW61k9S02YInSZLUAg0fDoMH51Y5CMaNy0ld69YwaBC89BL07QsR5Y5U0sKwBU+SJKkF+sMfqpK7arNnw5Ah+f7665vcSc2RCZ4kSVILNH78wpVLah5M8CRJklqAlODOO+GJJ/L2yivXflyPHo0Xk6SGZ4InSZJU4UaNgi23hJ13hvPOy2V/+hO0azf3ce3awdChjR+fpIZjgidJklShnnsOtt0WBgzIXS8vuSRPrgJ5IpVhw6BnT4hI9OyZtwcNKm/Mkr4dZ9GUJEmqUE88AS+/DOeeC7/8JbRtO/f+QYPybfToh+nXr19ZYpTUsGzBkyRJqhBvvQU/+1lesw7gkEPg3Xfh6KPnTe4kVSYTPEmSpGZu/Hg46CBYay247TaYMiWXL7EEdOhQ3tgkNS67aEqSJDVj554Lxx+f7x92WF7frlu38sYkqXxM8CRJkpqZyZOhdWvo2BFWWw322w/++EeXOJBkF01JkqRmY+rUvIxB795w1lm5bOed4dJLTe4kZbbgSZIkNXFffw3/+AeceSZ8+insuivssUe5o5LUFJngSZIkNXGHHAJXXQXbbAOnnw6bbVbuiCQ1VXbRlCRJamJmz84Lkr/3Xt4+7jgYORIeeMDkTtL8meBJkiQ1ESnBiBGw/vqwzz7wr3/l8nXWgf79yxubpObBBE+SJKkJePDB3Dq3++4waxbccAOcemq5o5LU3DgGT5IkqQm45Rb43//gsstg333zMgiStLBswZMkSSqDF16AHXaAxx/P23/6E4wZAwceaHInadGZ4EmSJDWi11+Hn/wEvvMdePpp+PDDXN6pEyyxRHljk9T8meBJkiQ1kqOPhvXWg/vugxNPhHffhT33LHdUkiqJHQAkSZJKaMIE6NYNFlsMevaEX/8ajj8eunYtd2SSKpEteJIkSSUwcSIceyysskqeERNycnf22SZ3kkrHFjxJkqQGNGUKnHMOnHsuTJuW17PbfPNyRyWppTDBkyRJakADB8JTT8GPf5zXsVt77XJHJKklMcGTJEn6FmbMgMsvz2vXtW8PZ5yRZ8TcaKNyRyapJTLBkyRJWgSzZsE118DJJ8O4cdCuHey3H/TvX+7IJLVkTrIiSZK0EFKCm26CddfNi5J37ZqXPdh333JHJkm24EmSJC20iy6C1q3h3/+G3XaDiHJHJEmZLXiSJEkLMGoU/OAH8OGHOZm78UZ4+WX40Y9M7iQ1LSZ4kiRJdXjmGdh2WxgwAMaMgXffzeXLLQetWpU3NkmqjQmeJElSDbNn52UONtsst9Sdcw68/TZstVW5I5Ok+XMMniRJUsEnn0C3brl1bqWV4PTT4aijoEOHckcmSfVjgidJklqc4cNhyBAYP35revSA3/wG/vMfuPJKePpp2HBDuOCCckcpSQvPBE+SJLUow4fD4MEwfTpAMG5cbqVr1QoOOyy33ElSc2WCJ0mSWpQhQ6qSu7ktvzycf37jxyNJDclJViRJUovx9dcwblzt+z76qHFjkaRSMMGTJEkVb/bsPL6uT5+6j+nRo/HikaRSMcGTJEkVKyW46y7YYAM44ABYdln4/e+hXbu5j2vXDoYOLUuIktSgHIMnSZIq1owZ8MtfwhJLwA03wE9+AostBuusUzWLZqJHj2DoUBg0qNzRStK3ZwueJEmqKGPG5KRuxgxo2xYeeADeeAP23DMnd5CTubFjYeTIhxk71uROUuUwwZMkSRXho4/gkENy69zw4fDSS7l8zTWhTZvyxiZJjcUET5IkNWszZuTulqutBpdfnteye+cd2GyzckcmSY3PMXiSJKlZSgkiYPHF4aGH4Ec/gtNOg1VWKXdkklQ+tuBJkqRmZfZsuOoq6NsXPv00J3mjR+dumSZ3klo6EzxJktQspAR33w0bbgj7759nxvz007yvbdvyxiZJTYUJniRJavJmzIABA2DHHWH69LzkwTPPwNprlzsySWpaHIMnSZKarE8/zYuTL7FETub22AMOOiiPu5MkzcsWPEmS1ORMmJDXsuvePa9hB3DRRXDooSZ3kjQ/tuBJkqQmY8oUOOssOPdcmDkzJ3ldu5Y7KklqPkraghcRAyNiTES8HRHH17K/R0SMiogXI+KViNihlPFIkqSma8aMvEj50KGwyy655e6CC3IXTUlS/ZQswYuIVsBFwA+BtYGfRkTNodAnADemlDYE9gb+Xqp4JElS0zN7Ntx7b54hc4kl4NRT4bnn4LrrYNVVyx2dJDU/peyiuSnwdkrpXYCIuB7YFXi96JgELFW43wn4aEEXbff++9CvX8NG2kxt8Pnn0LlzucMoO+uhmnVRzbqoZl1k1kO1plAXCfjsM3j3XWg7DaZsAJ07wc8bOY6mUBdNgfVQzbqoZl00T6VM8FYC3i/a/gDYrMYxJwP3R8QRQHtgm9ouFBGDgcEA67Zp0+CBSpKkxvPFl/DuO/D5lLx+3dprQadO5Y5KkipDuSdZ+SlwRUrprxHxXeDqiFg3pTSn+KCU0jBgGECfPn0So0c3fqRN0EujR9PP1kzroYh1Uc26qGZdZNZDtXLWxYwZsEZPmLM4nHghDB5c3lkxfV9k1kM166KaddGERdS5q5STrHwIdC/aXrlQVuwXwI0AKaUngbaAc2VJklRBPv4YTjwRZs3K4+xuvx3eeQcOP9wlDySpoZUywXsWWD0iekfE4uRJVG6vccx44AcAEbEWOcH7tIQxSZKkRvLFFzmxW3VVOPNMePrpXL7pptCxY3ljk6RKVbIEL6U0CzgcuA94gzxb5msRcWpE7FI47Bjg4Ih4GbgOOCCllEoVkyRJKr2ZM/PyBquuCqedBjvvnJc82HLLckcmSZWvpGPwUkp3A3fXKDux6P7rgH/uJUmqIIstBpdeCn37wp//DBtvXO6IJKnlKOlC55IkqfKlBPfdBz/4AUyZAq1awcMPw4MPmtxJUmMzwZMkSYvs2Wdhm21g4EB47718A1h66flO8iZJKhETPEmStNBmzIC99soTprzySh5z9+absMEG5Y5Mklq2cq+DJ0mSmpHp06Fdu7zcAeRZMo85BpZaqiKguBAAACAASURBVLxxSZIyEzxJkrRAX3wBZ58NF14Izz2XZ8i8/nq7YUpSU2OCJ0mS6jRjBlxySV7uYOLE3C2zTZu8z+ROkpoeEzxJklSrGTPyUgf//S8MGOCSB5LUHJjgSZKk/5cSvPgibLRRHmc3eDCstx5su60tdpLUHDiL5rfx+OOw3Xaw3HLQsWP+b3jZZfMe9/XXcOyxsMIKsOSS8N3vwiOPzH3M7Nnwu9/la3XvDuedN+91brwRVlwxD4RobOedB//+d8Nfd84cOProXDeLLQa77ZbL33wzf1281FL5E8Wtt9Z+/ujR9LriinydYmPH5vP++c+Gj3lhXXFFjuXttxv2emPHzv+4qjq44oqGeVxJFe+553Ii953vwBNP5LJjjsn/6kzuJKl5MMFbVK+8khf+mTkTLr00Jz+bbAK/+AX84x9zH/uLX+RjTj0V7rwzJzPbbw8vvVR9zJVX5kEOF1wAQ4bAb38Lo0dX7586FX7zG/jrX8szVVmpErybb4bzz88J8OOPw1/+kst/8xt4992c1D75JGy9de3njx5NryuvnDfBkyTV29tvw957539jL7+c/yx/5zvljkqStCjsormorr8+t7rdcQd06JDLtt02J35XXQW/+lUue/lluPba3LJ34IG5bOutYZ118tzSt9+ey+65B372s/wfFuC223JZv355++STYc014ac/baxn2DjeeCP/PPro3IJXXP797+eVcxtbSjlxX3zxxn9sSSqh4cPzd4jjx29Njx4wdCj85Cew5Zb5e8Q//jF/v+iSB5LUfNmCt6i++SZPI7bkknOXd+o0d2vS7bfn4/baq7qsdeucyN13Xx7BXnW94mu1a5e7dgK8+ipcfDFcdNHCxzliRP7P3aFD/o+96abVSWVdXfhGj87lVS2IvXrBuHH5k0FEvh1wwIIf+957c3fUJZfM9bLbbjBmTPX+Xr1y4grQqlV1LFXdD6++uvrxanPyyXDKKfl+mza1Hzt7dk6kV1gBOneGnXeGDz6Y+5hevWCffXISvuaaObG766687+WXYZddoEuX/Dy23BIefXTu8599Nif3yyyTj1llFTj00HnjnTgRBg3Kr8OKK8KRR1a/xlUmTID99oOuXfPgl7594Zpran/+xaZPh0MPZctdd82v9S67zPs8JbVow4fn8XTjxkFKwbhxefvmm/OfmXfeyR1NTO4kqXkzwVtUVQnOkUfCRx/B55/nbpgPPQS//nX1ca+9Br1754St2Drr5KSualzWZpvBLbfk7eefh/vvh803z/sOPTS3cPXps3AxXngh7L57Htd35ZVw003wox8teOxWTSNGwPLL526lTz6Zb3/84/zPufde2HHHnGzccEPutvrqq/C978GHH1Zft6oeq67bv3/+ueyysMMO1eW1Oeig3P0V4LHHaj/2zDNznV52We5z9OSTOZmradQoOOccOOmkHHvfvvDCC7DFFvDZZ/m1veWWnMRts01+jSB/5b399jlBveKK3Op64okwa9a8j7HvvnnhqH//O7fwXnRRjq/KtGm5dfeee+CMM/K4w/XWy+cNGzb/+j7kEPjnP3l/jz3y9fv0yS3CklQwZEj+LqjY9Om5fNtt8595SVLzZxfNRbXuurmF60c/gr//PZe1aZNb2qq6WUJODrp0mff8pZeu3g9wxBE5qVt99by999651e+qq3JLzJAhCxffF1/AH/6Q4yseO7f99gt3HYANN8ytSV27ViedC3LCCbkl6557cosl5Na8NdbI4wjPOSdfd6WV8r7i6/bsmVvRll12/o+38sr5BjlBbl3L27lXr9xFtsqnn+bxfh99lFvRqkyenJO24k84P/gB9OgBI0dWd9fcfvv82p92Wk7A3nwzn/uXv+SksEptLZw/+1l1i+M228DTT8N111WXXX45vPVWTjaruub+8IfwySe5Pn/xi5xI1jRmTH6OQ4cyfvPNWaVfvzwjwtSp+f0oScD48QtXLklqnmzBW1RvvQU//nFuibvjDnjwQfjlL/Nt+PCFv17HjjlhHDs2Jx/XXZeTtGOPzS1xSyyRk7yVV85J0ZAh859Y5Ikn8gf8wYMX9RkuWEq5par4Brkl6oUXcoJanHT17p27OD78cOliqmmHHebeXm+9/LPmJ5rNN587ufvqqxznHnvksYFVzy+lnJxVzYK6+uq56+chh+Q+Tu+/X3csO+44byzFcTzySH5tq5K7KvvskxPT11+v/bpPP53fC3vuOXd58RcNklq0mTNr/34I8vdYkqTKYYK3qP7wh9xid+edsNNOubXnggvyh+yjjqpOvrp0yS08NVW13FW15FXp2TOPF4OcxG2xRU4M/vWvnEA8+mjujnj11Sx/zz11xzdpUv5Z1cJVCg8/nOug+Ab5+aZU/TyKLb989XNvDDXrd4kl8s+aY99qxvrZZ3n83mmnzfsc//a3/BznzMljC0eNyq2Bhx6aPymtu27uzlmfWKrGYFY9Zl11VrW/NhMm5J/dus1dXnNbUovy2Wf538i0aflP15/+NO9ogXbt8kQrkqTKYRfNRfWf/8D661cnNVU23TR3l/vf//IH83XWyWPNpk+f+z/r66/nbn+rrVb79Z9/Pk8y8uqrefvee/NUZ7175+099mDpZ5+tO76uXfPPDz/MCUdt2rbNP7/5Zu7yquRwQb7znTzBSE1duuTJTj7+eN59H388b6LTFNScnKVz59xyd9hhedKT2lTN+rnBBjmhmzUrLyJ15pk50X/55brrvjZLLz33JDRVquqxrnqrSgo/+WTu8prbklqEmTNz7+yTToIpU3IHhZ13zuvZLb981SyaiR49gqFD89xPkqTKYQveolp++byOXc3k6Omnc+JU9WF8553zf9ubbqo+ZtasPPHIdttVtygVmzMntwadcMLcfWemTau+P3UqkVLd8W2xRZ7gZH6Tc3Trlh+/KomsUjWDZLEllsjdFot17Agbbzz3DaB9+5z83XRTbgWrMm5c7jpaswvit1FVfzVj+7bat4ettspJ2kYbzfs8q55rsdat8yep007Lr2HVEhD1tfXWebzl44/PXX7ttXminLXXrv28zTbLyeaNN85dfv31C/f4kpq9e+/N3z0eeWQe5vzii/nfUJVBg/JIgJEjH2bsWJM7SapEtuAtqsMPz+Ozdt45J2NLLpmXH7juujyLZtWkHBtumMeiHX10TvR6984zSr73Xt1j9S69NCdzxbNxbrMN/O53OekAuPZaPhs8mGXriq9jx9ySdMQReazgoEG57KWXcgJ6xBG51Wqv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)
