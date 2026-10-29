## Triangle:

- **Median:** A line segment from a vertex to the midpoint of the opposite edge.

- **Altitude:** A perpendicular line segment from a vertex to the opposite edge.

- **Centroid (G):** Intersection of all the medians. Center of mass. At the centroid, each median is divided in 2:1 ratio. It is the average of coordinates of the vertices - $\left( \dfrac{x_1+x_2+x_3}{3}, \dfrac{y_1+y_2+y_3}{3} \right)$

- **Orthocenter (H):** Intersection of all the altitudes.

- **Incenter (I):** Intersection of all the angle bisectors. Center of the incircle. Equidistant from all sides. $\left( \dfrac{ax_1+bx_2+cx_3}{a + b + c},\ \dfrac{ay_1+by_2+cy_3}{a + b + c} \right)$ $a, b, c$ are length of the sides.

- **Circumcenter (O):** Intersection of the perpendicular bisectors of all the sides. Center of the circumcircle. Equidistant from all vertices. $\left( \dfrac{x_1\sin 2A + x_2\sin 2B + x_3\sin 2C}{\sin 2A + \sin 2B + \sin 2C}, \dfrac{y_1\sin 2A + y_2\sin 2B + y_3\sin 2C}{\sin 2A + \sin 2B + \sin 2C} \right)$

- **Position of centers:**

  | <th><th>             | Centroid (G) | Incentre (I) | Orthocentre (H) | Circumcentre (O) |
  | -------------------- | ------------ | ------------ | --------------- | ---------------- |
  | <th>Acute<th>        | In           | In           | In              | In               |
  | <th>Right Angled<th> | In           | In           | Perimeter       | Perimeter        |
  | <th>Obtuse<th>       | In           | In           | Out             | Out              |

- **Area of triangle:** <br>
  $` A = \dfrac{1}{2}\begin{vmatrix}x_1&y_1&1\\x_2&y_2&1\\x_3&y_3&1\end{vmatrix} = \dfrac{1}{2} * | x1 (y2 - y3) + x2 (y3 - y1) + x3 (y1 - y2) | `$ <br>
  If this is 0, the 3 points are colinear

## Point and Segment:

- **Distance between 2 points:** $d = \sqrt{{(x_2 - x_1)}^2 + {(y_2 - y_1)}^2}$

- **Internal Section formula:** $P(x,y) = \left( {\dfrac{{m{x_2} + n{x_1}}}{{m + n}},\dfrac{{m{y_2} + n{y_1}}}{{m + n}}} \right)$ where $P$ internally divides the line segment into the ratio $m:n$

- **External Section formula:** $P(x,y) = \left( {\dfrac{{m{x_2} - n{x_1}}}{{m - n}},\dfrac{{m{y_2} - n{y_1}}}{{m - n}}} \right)$

## Line:

- **Slope (m):**
  - $m = \tan\theta$, where $\theta$ is the angle the line subtends on the X-axis.
  - $m = \dfrac{y_2-y_1}{x_2-x_1}$ where $(x_1,y_1)$ and $(x_2,y_2)$ are 2 points on the line.

- **Equations:**
  - **Slope-point form:** $y-y_1 = m(x-x_1)$

  - **Two point form:** $\dfrac{y-y_1}{x-x_1} = \dfrac{y_2-y_1}{x_2-x_1}$

  - **Slope-intercept form:** $y=mx+c$ where $c$ is the y-intercept

  - **Double intercept form:** $\dfrac{x}{a}+\dfrac{y}{b}=1$ where $a$ is the X-intercept and $b$ is the Y-intercept

  - **General form:** $ax+by+c=0$
    - **Slope:** $m=\dfrac{-a}{b}$

    - **X-intercept:** $\dfrac{-c}{a}$

    - **Y-intercept:** $\dfrac{-c}{b}$

  - **Normal form:** $x\cos\alpha+y\sin\alpha=p$ where $p$ is the perpendicular distance from the origin to the line, and $\alpha$ is the angle made by the perpendicular with the X-axis

- **Perpendicular lines:** If 2 lines having slopes $m_1$ and $m_2$ are perpendicular, then $m_1m_2=-1$

- **Important points:**
  - If $L_1 \Rightarrow ax+by+c_1=0$, and $L_1 \parallel L_2$, then $L_2 \Rightarrow ax+by+c_2=0$
  - If $L_1 \Rightarrow ax+by+c_1=0$, and $L_1 \perp L_2$, then $L_2 \Rightarrow bx-ay+c_2=0$

- **Angle between 2 lines:** $\tan\theta = \left|\dfrac{m_1 - m_2}{1 + m_1m_2}\right|$

- **Distance of a point from a line:** $d = \dfrac{|ax_1 + by_1 + c|}{\sqrt{a^2 + b^2}} $ where $(x_1,y_1)$ is the point, and $ax+by+c=0$ is the equation of the line.

- **Distance between parallel lines:** For 2 parallel lines in the general form $ax+by+c=0$, their $a$, and $b$ values will be the same. $d=\dfrac{|c_1-c_2|}{\sqrt{a^2+b^2}}$

- **Angle bisector of two lines:** Given two lines $L_1 \Rightarrow a_1x+b_1y+c_1=0$, and $L_2 \Rightarrow a_2x+b_2y+c_2=0$, then the equation of their angle bisector is $\left|\dfrac{a_1x+b_1y+c_1}{\sqrt{a_1^2+b_1^2}}\right|=\left|\dfrac{a_2x+b_2y+c_2}{\sqrt{a_2^2+b_2^2}}\right|$

- **Consistency of lines:** If 3 or more lines intersect at the same point, those lines are said to be consistent. 3 lines are consistent if $ \begin{vmatrix}a_1&b_1&c_1\\a_2&b_2&c_2\\a_3&b_3&c_3\end{vmatrix} = 0$

- **Point of intersection between 2 lines:** It can be found by simultaneously solving both the equations.

- **Homogenous equation for pair of 2 lines passing through origin:** $ax^2+2hxy+by^2=0$
  - If $h^2>ab$, the lines are distinct and real
  - If $h^2=ab$, the lines are real and identical
  - If $h^2<ab$, the lines are imaginary
  - Slopes of the lines $m = \dfrac{-h \pm \sqrt{h^2-ab}}{b}$
  - Angle between the lines: $\tan\theta=\left|\dfrac{2\sqrt{h^2-ab}}{a+b}\right|$
    - If $a+b=0,\theta=90^\circ$
    - If $h^2=ab,\theta=0^\circ$ ie the lines coincide.

## Circle:

- **Equation:** Where $r$ is radius
  - **Center-radius Form:** $(x - h)^2 + (y - k)^2 = r^2$ where $(h,k)$ is the center
  - **Diameter Form:** $(x-x_1)(x-x_2)+(y-y_1)(y-y_2)=0$ where $(x_1,y_1)$ and $(x_2,y_2)$ are the endpoints of a diameter of the circle.
  - **Parametric Form:** $P(x,y)=(h+r\cos\theta,k+r\sin\theta)$ where $(h,k)$ is the center
  - **General Form:** $x^2+y^2+2gx+2fy+c=0$
    - Center $=(-g,-f)$
    - Radius $=\sqrt{g^2+f^2-c}$
    - **Properties:**
      - If $g^2>c$, then circle will cut X-axis at 2 distinct points
      - If $g^2=c$, then circle will touch X-axis at a point
      - If $g^2<c$, then circle will neither touch not cut the X-axis
      - Same with $f^2$ and Y-axis
      - If $c=0$, the circle passes through the origin

## Parabola :

- **Equation:** $y^2=4ax$
  - **Focus:** $(a,0)$
  - **Directrix:** $x=-a$
  - **l(Latus Rectum):** $4a$
  - **Focal distance:** Distance from a point $P(x,y)$ on the parablola to the focus is $x+a$
  - **Eccentricity:** $e=1$
- **General equation:** $ax^2+2hxy+by^2+2gx+2fy+c=0$ if $abc+fgh-af^2-bg^2-ch^2=0$ and $ab-h^2=0$
- **Parametric equations:** <br>
  | Standard Equation | Parametric Equation |
  |-------------------|---------------------|
  | $y^2=4ax$ | $(at^2,2at)$ |
  | $y^2=-4ax$ | $(-at^2,2at)$ |
  | $x^2=4ay$ | $(2at,at^2)$ |
  | $x^2=-4ay$ | $(2at,-at^2)$ |
  - **Focal chord:** A chord passing through the focus of the parabola has its endpoints at $(at_1^2,2at_1)$ and $(at_2^2,2at_2)$ where $t_1 \times t_2 = -1$. <br> $\therefore$ Endpoints $= (at^2,2at)$, and $\left(\dfrac{a}{t^2},\dfrac{-2a}{t}\right)$
  - **Endpoints of latus rectum:** $(a,2a)$ and $(a,-2a)$ because $t=1$ at the endpoints of the latus rectum.
- **Position of point $P(h,k)$ wrt parabola:**
  $k^2-4ah = \begin{cases}
  \gt 0 \Rightarrow \text{outside} \\
  = 0 \Rightarrow \text{on the parabola} \\
  \lt 0 \Rightarrow \text{inside} \\
  \end{cases}$

## Ellipse :

- **Standard Equation:** $\dfrac{x^2}{a^2}+\dfrac{y^2}{b^2}=1$
- **Parametric Form:** $P(x,y)=(a\cos\theta,b\sin\theta)$
- **Properties:**
  - **Directrix:** Line parallel to Latus Rectum, and perpendicular to Major axis
  - **l(Major axis):** $2a$
  - **l(Minor axis):** $2b$
  - **Double Ordinate:** Chord perpendicular to the major axis
  - **Latus Rectum:** A double ordinate that passes through a focus
  - **Eccentricity:**
    - $e=\dfrac{PS}{PM}$ where $P$ is a point on the ellipse, $S$ is a focus, and $M$ is a directrix.
  - **Focal distance:** Distance of a point $P(x,y)$ from the focii of an ellipse.

  |                               | $\|a\| > \|b\|$                           | $\|b\| > \|a\|$                           |
  | ----------------------------- | ----------------------------------------- | ----------------------------------------- |
  | **Focii**                     | $(\pm ae,0)$                              | $(\pm be,0)$                              |
  | **Directrix**                 | $x=\pm\dfrac{a}{e}$                       | $y=\pm\dfrac{b}{e}$                       |
  | **l(Latus Rectum)**           | $\dfrac{2b^2}{a}$                         | $\dfrac{2a^2}{b}$                         |
  | **Eccentricity**              | $e^2=1-\dfrac{b^2}{a^2}$                  | $e^2=1-\dfrac{a^2}{b^2}$                  |
  | **Endpoints of Latus Rectum** | $\left(\pm ae, \pm \dfrac{b^2}{a}\right)$ | $\left(\pm be, \pm \dfrac{a^2}{b}\right)$ |
  | **Focal Distance**            | $a\pm ex$                                 | $b\pm ex$                                 |
  - **Director Circle:** $x^2+y^2=a^2+b^2$

## Hyperbola :

- **Equation:** $\dfrac{x^2}{a^2}-\dfrac{y^2}{b^2}=1$
  - **Focii:** $(-ae,0),(+ae,0)$
  - **Vertices:** $(-a,0),(a,0)$
  - **Directrix:** $x=\pm\dfrac{a}{e}$
  - **l(Trnsverse axis):** $2a$
  - **l(Conjugate axis):** $2b$
  - **Eccentricity:** $e=\sqrt{1-\dfrac{b^2}{a^2}}$
  - **Note: Flip a and b if b > a**

## Tranformations:

- **Shift of origin:** $x'=x-h, y'=y-k$ where $(h,k)$ is the new origin.
- **Rotation:** $\theta$ is the angle of rotation

  |      | $x$           | $y$          |
  | ---- | ------------- | ------------ |
  | $x'$ | $\cos\theta$  | $\sin\theta$ |
  | $y'$ | $-\sin\theta$ | $\cos\theta$ |

## Miscellaneous:

- Sum of external angles of any polygon $=360^\circ$
- Sum of internal angles of a polygon $=(n-2)*180^\circ$, where $n$ is the number of sides.
