# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.003 ops/ms
# Warmup Iteration   2: 2.102 ops/ms
# Warmup Iteration   3: 4.595 ops/ms
Iteration   1: 5.304 ops/ms
Iteration   2: 5.589 ops/ms
Iteration   3: 5.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.515 ±(99.9%) 3.381 ops/ms [Average]
  (min, avg, max) = (5.304, 5.515, 5.651), stdev = 0.185
  CI (99.9%): [2.134, 8.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.297 ops/ms
# Warmup Iteration   2: 4.223 ops/ms
# Warmup Iteration   3: 5.507 ops/ms
Iteration   1: 5.723 ops/ms
Iteration   2: 5.603 ops/ms
Iteration   3: 5.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.734 ±(99.9%) 2.489 ops/ms [Average]
  (min, avg, max) = (5.603, 5.734, 5.875), stdev = 0.136
  CI (99.9%): [3.245, 8.222] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.322 ops/ms
# Warmup Iteration   2: 3.746 ops/ms
# Warmup Iteration   3: 5.439 ops/ms
Iteration   1: 5.296 ops/ms
Iteration   2: 5.437 ops/ms
Iteration   3: 5.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.359 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (5.296, 5.359, 5.437), stdev = 0.072
  CI (99.9%): [4.052, 6.666] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.299 ops/ms
# Warmup Iteration   2: 3.280 ops/ms
# Warmup Iteration   3: 4.645 ops/ms
Iteration   1: 4.605 ops/ms
Iteration   2: 4.768 ops/ms
Iteration   3: 4.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.694 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (4.605, 4.694, 4.768), stdev = 0.083
  CI (99.9%): [3.184, 6.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 22.044 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 7.904 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.483 ±(99.9%) 0.007 ms/op
Iteration   1: 5.951 ±(99.9%) 0.021 ms/op
Iteration   2: 5.831 ±(99.9%) 0.013 ms/op
Iteration   3: 5.809 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.863 ±(99.9%) 1.396 ms/op [Average]
  (min, avg, max) = (5.809, 5.863, 5.951), stdev = 0.077
  CI (99.9%): [4.467, 7.260] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.060 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.443 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.493 ±(99.9%) 0.011 ms/op
Iteration   1: 5.385 ±(99.9%) 0.009 ms/op
Iteration   2: 5.458 ±(99.9%) 0.012 ms/op
Iteration   3: 5.379 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.407 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (5.379, 5.407, 5.458), stdev = 0.044
  CI (99.9%): [4.607, 6.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 20.145 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.634 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.705 ±(99.9%) 0.021 ms/op
Iteration   1: 5.921 ±(99.9%) 0.011 ms/op
Iteration   2: 5.748 ±(99.9%) 0.009 ms/op
Iteration   3: 5.703 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.791 ±(99.9%) 2.105 ms/op [Average]
  (min, avg, max) = (5.703, 5.791, 5.921), stdev = 0.115
  CI (99.9%): [3.686, 7.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.193 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 8.409 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 7.176 ±(99.9%) 0.011 ms/op
Iteration   1: 6.807 ±(99.9%) 0.014 ms/op
Iteration   2: 6.719 ±(99.9%) 0.014 ms/op
Iteration   3: 6.866 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.797 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (6.719, 6.797, 6.866), stdev = 0.074
  CI (99.9%): [5.451, 8.144] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.092 ±(99.9%) 0.370 ms/op
# Warmup Iteration   2: 8.090 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.490 ±(99.9%) 0.032 ms/op
Iteration   1: 5.822 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   7.291 ms/op
                 createUser·p0.95:   8.831 ms/op
                 createUser·p0.99:   12.332 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 30.212 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   2: 5.987 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.071 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.645 ms/op
                 createUser·p0.999:  28.575 ms/op
                 createUser·p0.9999: 32.330 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   3: 5.751 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   11.633 ms/op
                 createUser·p0.999:  31.943 ms/op
                 createUser·p0.9999: 35.912 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163944
  mean =      5.852 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 33090 
    [ 5.000,  7.500) = 117495 
    [ 7.500, 10.000) = 9564 
    [10.000, 12.500) = 2465 
    [12.500, 15.000) = 817 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.071 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.372 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     22.710 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     37.841 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.803 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.828 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.580 ±(99.9%) 0.022 ms/op
Iteration   1: 5.679 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.094 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   11.059 ms/op
                 existUser·p0.999:  14.615 ms/op
                 existUser·p0.9999: 28.770 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   2: 5.620 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   6.857 ms/op
                 existUser·p0.95:   8.069 ms/op
                 existUser·p0.99:   11.272 ms/op
                 existUser·p0.999:  31.556 ms/op
                 existUser·p0.9999: 35.234 ms/op
                 existUser·p1.00:   36.504 ms/op

Iteration   3: 5.622 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.580 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   7.045 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   11.960 ms/op
                 existUser·p0.999:  30.709 ms/op
                 existUser·p0.9999: 39.167 ms/op
                 existUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170006
  mean =      5.640 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 49818 
    [ 5.000,  7.500) = 107586 
    [ 7.500, 10.000) = 8964 
    [10.000, 12.500) = 2699 
    [12.500, 15.000) = 547 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.004 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     19.693 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     39.643 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.685 ±(99.9%) 0.375 ms/op
# Warmup Iteration   2: 7.246 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.846 ±(99.9%) 0.021 ms/op
Iteration   1: 5.852 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.250 ms/op
                 getUser·p0.95:   8.438 ms/op
                 getUser·p0.99:   11.829 ms/op
                 getUser·p0.999:  23.406 ms/op
                 getUser·p0.9999: 28.477 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 5.869 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.994 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.878 ms/op
                 getUser·p0.999:  25.216 ms/op
                 getUser·p0.9999: 35.193 ms/op
                 getUser·p1.00:   35.521 ms/op

Iteration   3: 5.776 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.855 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   7.891 ms/op
                 getUser·p0.99:   11.224 ms/op
                 getUser·p0.999:  26.926 ms/op
                 getUser·p0.9999: 30.281 ms/op
                 getUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164491
  mean =      5.832 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 34890 
    [ 5.000,  7.500) = 117071 
    [ 7.500, 10.000) = 8680 
    [10.000, 12.500) = 2447 
    [12.500, 15.000) = 911 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.372 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     25.314 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     35.590 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.116 ±(99.9%) 0.383 ms/op
# Warmup Iteration   2: 8.434 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 7.393 ±(99.9%) 0.036 ms/op
Iteration   1: 6.884 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.356 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   12.641 ms/op
                 listUser·p0.999:  34.508 ms/op
                 listUser·p0.9999: 37.182 ms/op
                 listUser·p1.00:   39.911 ms/op

Iteration   2: 6.864 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.199 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   13.357 ms/op
                 listUser·p0.999:  32.331 ms/op
                 listUser·p0.9999: 36.372 ms/op
                 listUser·p1.00:   37.683 ms/op

Iteration   3: 6.792 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   12.534 ms/op
                 listUser·p0.999:  28.730 ms/op
                 listUser·p0.9999: 32.010 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140176
  mean =      6.846 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2490 
    [ 5.000,  7.500) = 112418 
    [ 7.500, 10.000) = 19422 
    [10.000, 12.500) = 4224 
    [12.500, 15.000) = 956 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 81 
    [32.500, 35.000) = 75 
    [35.000, 37.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.913 ms/op
     p(50.0000) =      6.431 ms/op
     p(90.0000) =      8.331 ms/op
     p(95.0000) =      9.650 ms/op
     p(99.0000) =     12.763 ms/op
     p(99.9000) =     31.484 ms/op
     p(99.9900) =     36.502 ms/op
     p(99.9990) =     39.016 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.515 ± 3.381  ops/ms
ClientPb.existUser                       thrpt       3   5.734 ± 2.489  ops/ms
ClientPb.getUser                         thrpt       3   5.359 ± 1.307  ops/ms
ClientPb.listUser                        thrpt       3   4.694 ± 1.510  ops/ms
ClientPb.createUser                       avgt       3   5.863 ± 1.396   ms/op
ClientPb.existUser                        avgt       3   5.407 ± 0.800   ms/op
ClientPb.getUser                          avgt       3   5.791 ± 2.105   ms/op
ClientPb.listUser                         avgt       3   6.797 ± 1.346   ms/op
ClientPb.createUser                     sample  163944   5.852 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.372           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.862           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.710           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.062           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.470           ms/op
ClientPb.existUser                      sample  170006   5.640 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.470           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.004           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.315           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.076           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.780           ms/op
ClientPb.getUser                        sample  164491   5.832 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.888           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.102           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.372           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.026           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.314           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.603           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.717           ms/op
ClientPb.listUser                       sample  140176   6.846 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.913           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.331           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.650           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.763           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.484           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.911           ms/op
