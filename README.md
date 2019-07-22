[![Build Status](https://travis-ci.org/onsense/universe.svg?branch=master)](https://travis-ci.org/onsense/universe) [ ![Download](https://api.bintray.com/packages/onsense/universe/onsense-universe/images/download.svg) ](https://bintray.com/onsense/universe/onsense-universe/_latestVersion)

# universe

Java implementation of most Excel formula functions.

# USAGE
Functions are divided over the classes
- Expresions
- Financials
- Formulas
- Informations
- Logicals
- Lookups
- Moments
- Statistics

## Usage with maven
```
<dependency>
  <groupId>io.onsense</groupId>
  <artifactId>universe</artifactId>
  <version>1.0.5</version>
  <type>jar</type>
</dependency>
```

Download or copy the Maven settings:
```
<?xml version="1.0" encoding="UTF-8" ?>
<settings xsi:schemaLocation='http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd'
          xmlns='http://maven.apache.org/SETTINGS/1.0.0' xmlns:xsi='http://www.w3.org/2001/XMLSchema-instance'>
    
    <profiles>
        <profile>
            <repositories>
                <repository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>bintray-onsense-universe</id>
                    <name>bintray</name>
                    <url>https://dl.bintray.com/onsense/universe</url>
                </repository>
            </repositories>
            <pluginRepositories>
                <pluginRepository>
                    <snapshots>
                        <enabled>false</enabled>
                    </snapshots>
                    <id>bintray-onsense-universe</id>
                    <name>bintray-plugins</name>
                    <url>https://dl.bintray.com/onsense/universe</url>
                </pluginRepository>
            </pluginRepositories>
            <id>bintray</id>
        </profile>
    </profiles>
    <activeProfiles>
        <activeProfile>bintray</activeProfile>
    </activeProfiles>
</settings>
```

# LICENSE
Universe is freely distributable under the terms of the MIT license. Copyright (c) 2019 onsense.

# FUNCTIONS
List of functions per class
- Expresions  
  - concat
  - lower
  - toLowerCase
  - upper
  - toUpperCase
  - chop
  - charr
  - code
  - clean
  - concatenate
  - dollar
  - exact
  - find
  - fixed
  - left
  - right
  - len
  - mid
  - numbervalue
  - proper
  - search
  - substitute
  - t
  - text
  - unichar
  - unicode
  - value
  - isPrintable
  - trim
  - ltrim
  - trimLeft
  - rtrim
  - trimRight
  - rept
  - repeat
  - prefix
  - suffix
  - capitalize
  - capitalizeFully
  - decapitalize
  - decapitalizeFully
  - substring
  - remove
  - removeFirst
  - removeLast
  - replace
  - replaceFirst
  - replaceLast
  - reverse
  - initials
  - swap
  - quote
  - unquote
  - format
  - random
  - encode
  - decode
  - atob
  - btoa
  - hex
  - md2
  - md5
  - sha256
  - crc32
- Financials
  - accrint
  - accrintm
  - amordegrc
  - amorlinc
  - coupdaybs
  - coupdays
  - coupdaysnc
  - coupncd
  - coupnum
  - couppcd
  - cumipmt
  - cumprinc
  - db
  - ddb
  - disc
  - dollarde
  - dollarfr
  - duration
  - effect
  - fv
  - fvschedule
  - intrate
  - ipmt
  - irr
  - ispmt
  - mduration
  - mirr
  - nominal
  - nper
  - npv
  - oddfprice
  - oddfyield
  - oddlprice
  - oddlyield
  - pduration
  - pmt
  - ppmt
  - price
  - pricedisc
  - pricemat
  - pv
  - rate
  - received
  - rri
  - sln
  - syd
  - tbilleq
  - tbillprice
  - tbillyield
  - vdb
  - xirr
  - irr_result
  - irr_result_deriv
  - xnpv
  - yield
  - yielddisc
  - yieldmat
- Formulas
  - besseli
  - besselj
  - besselk
  - bessely
  - bin2dec
  - bin2hex
  - bin2oct
  - bitand
  - bitlshift
  - bitor
  - bitrshift
  - bitxor
  - complex
  - combin
  - combina
  - trunc
  - subtotal
  - sumif
  - buildIfCriteriaIndex
  - buildIfPredicate
  - buildNumericIfPredicate
  - sumifs
  - sumproduct
  - sumsq
  - sumx2my2
  - sumx2py2
  - sumxmy2
  - aggregate
  - large
  - small
  - decimal
  - dec2bin
  - dec2hex
  - dec2oct
  - delta
  - erf
  - erfc
  - erf_precise
  - gestep
  - hex2bin
  - hex2dec
  - hex2oct
  - mround
  - multinomial
  - imabs
  - imaginary
  - isNaN
  - imargument
  - imconjugate
  - imcos
  - imcosh
  - imcot
  - imcsc
  - imcsch
  - imdiv
  - imexp
  - imln
  - imlog10
  - imlog2
  - impower
  - improduct
  - imreal
  - imsec
  - imsech
  - imsin
  - imsinh
  - imsqrt
  - imsub
  - imsum
  - imtan
  - oct2bin
  - oct2dec
  - oct2hex
  - minus
  - plus
  - cos
  - tan
  - sin
  - acos
  - acosh
  - acot
  - acoth
  - asinh
  - atanh
  - base
  - choose
  - count
  - counta
  - convert
  - cot
  - coth
  - csc
  - csch
  - even
  - odd
  - fact
  - factdouble
  - gcd
  - lcm
  - lcmGcd
  - lcmLcm
  - geomean
  - harmean
  - product
  - sign
  - sec
  - sech
  - sqrtpi
  - atan
  - atan2
  - asin
  - sinh
  - tanh
  - cosh
  - log
  - log10
  - log2
  - ln
  - sqrt
  - abs
  - ceiling
  - ceil
  - floor
  - round
  - rounddown
  - roundup
  - mdeterm
  - power
  - quotient
  - radians
  - rad
  - degrees
  - deg
  - exp
  - cbrt
  - mod
  - hypot
  - root
  - factorial
  - bernoulli
  - mantissa
  - integral
  - fraction
  - min
  - max
  - sum
  - avg
  - mean
  - range
  - mode
  - median
- Informations
  - cell
  - errorType
  - info
  - isBlank
  - isErr
  - isError
  - isEven
  - isFormula
  - isLogical
  - isNa
  - isNonText
  - isNumber
  - isOdd
  - isRef
  - isText
  - n
  - na
  - sheet
  - sheets
  - type
- Logicals
  - logicalIf
  - logicalTrue
  - logicalFalse
  - logicalNot
  - logicalAnd
  - logicalOr
  - logicalXor
  - logicalSwitch
- Lookups
  - address
  - areas
  - choose
  - column
  - columns
  - formulatext
  - getpivotdata
  - hlookup
  - hyperlink
  - index
  - indirect
  - lookup
  - match
  - offset
  - row
  - rows
  - rtd
  - transpose
  - vlookup
- Moments
  - date
  - datedif
  - datevalue
  - day
  - days
  - days360
  - edate
  - eomonth
  - hour
  - isoweeknum
  - minute
  - month
  - networkdays
  - networkdays_intl
  - now
  - second
  - time
  - timevalue
  - today
  - weekday
  - weeknum
  - workday
  - workday_intl
  - year
  - yearfrac
  - yearfrac2
  - feb29Between
  - isLeapYear
  - timenow
  - datetimevalue
  - week
- Statistics
  - avedev
  - average
  - averagea
  - averageif
  - averageifs
  - beta_dist
  - beta_inv
  - binom_dist
  - binom_dist_range
  - binom_inv
  - chisq_dist
  - chisq_dist_rt
  - chisq_inv
  - chisq_inv_rt
  - chisq_test
  - confidence_norm
  - confidence_t
  - correl
  - count
  - counta
  - countblank
  - countif
  - countifs
  - covariance_p
  - covariance_s
  - devsq
  - expon_dist
  - f_dist
  - f_dist_rt
  - f_inv
  - f_inv_rt
  - f_test
  - fisher
  - fisherinv
  - forecast
  - forecast_ets
  - forecast_ets_confint
  - forecast_ets_seasonality
  - forecast_ets_stat
  - forecast_linear
  - frequency
  - gamma
  - gamma_dist
  - gamma_inv
  - gammaln
  - gammaln_precise
  - gauss
  - geomean
  - growth
  - harmean
  - hypgeom_dist
  - intercept
  - kurt
  - large
  - linest
  - logest
  - lognorm_dist
  - lognorm_inv
  - max
  - maxa
  - maxifs
  - median
  - min
  - mina
  - minifs
  - mode_mult
  - mode_sngl
  - negbinom_dist
  - norm_dist
  - norm_inv
  - norm_s_dist
  - norm_s_inv
  - pearson
  - percentile_exc
  - percentile_inc
  - percentrank_exc
  - percentrank_inc
  - unique
  - permut
  - permutationa
  - phi
  - poisson_dist
  - prob
  - quartile_exc
  - quartile_inc
  - rank_avg
  - rank_eq
  - rsq
  - skew
  - skew_p
  - slope
  - small
  - standardize
  - stdev_p
  - stdev_s
  - stdeva
  - stdevpa
  - steyx
  - t_dist
  - t_dist_2t
  - t_dist_rt
  - t_inv
  - t_inv_2t
  - t_test
  - trend
  - trimmean
  - var_p
  - var_s
  - vara
  - varpa
  - weibull_dist
  - z_test
  