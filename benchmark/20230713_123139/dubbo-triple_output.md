# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.910 ops/ms
# Warmup Iteration   2: 1.994 ops/ms
# Warmup Iteration   3: 4.323 ops/ms
Iteration   1: 5.189 ops/ms
Iteration   2: 5.318 ops/ms
Iteration   3: 5.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.311 ±(99.9%) 2.150 ops/ms [Average]
  (min, avg, max) = (5.189, 5.311, 5.425), stdev = 0.118
  CI (99.9%): [3.161, 7.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:20
# Fork: 1 of 1
# Warmup Iteration   1: 1.545 ops/ms
# Warmup Iteration   2: 4.547 ops/ms
# Warmup Iteration   3: 5.706 ops/ms
Iteration   1: 5.392 ops/ms
Iteration   2: 5.581 ops/ms
Iteration   3: 5.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.579 ±(99.9%) 3.395 ops/ms [Average]
  (min, avg, max) = (5.392, 5.579, 5.765), stdev = 0.186
  CI (99.9%): [2.184, 8.975] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.276 ops/ms
# Warmup Iteration   2: 4.039 ops/ms
# Warmup Iteration   3: 5.194 ops/ms
Iteration   1: 5.382 ops/ms
Iteration   2: 5.181 ops/ms
Iteration   3: 5.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.294 ±(99.9%) 1.875 ops/ms [Average]
  (min, avg, max) = (5.181, 5.294, 5.382), stdev = 0.103
  CI (99.9%): [3.419, 7.169] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.334 ops/ms
# Warmup Iteration   2: 3.491 ops/ms
# Warmup Iteration   3: 4.509 ops/ms
Iteration   1: 4.379 ops/ms
Iteration   2: 4.629 ops/ms
Iteration   3: 4.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.486 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (4.379, 4.486, 4.629), stdev = 0.129
  CI (99.9%): [2.142, 6.831] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:56
# Fork: 1 of 1
# Warmup Iteration   1: 22.119 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.347 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.330 ±(99.9%) 0.016 ms/op
Iteration   1: 6.254 ±(99.9%) 0.015 ms/op
Iteration   2: 6.223 ±(99.9%) 0.017 ms/op
Iteration   3: 5.937 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.138 ±(99.9%) 3.192 ms/op [Average]
  (min, avg, max) = (5.937, 6.138, 6.254), stdev = 0.175
  CI (99.9%): [2.946, 9.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.149 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.646 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.796 ±(99.9%) 0.009 ms/op
Iteration   1: 5.700 ±(99.9%) 0.014 ms/op
Iteration   2: 5.679 ±(99.9%) 0.014 ms/op
Iteration   3: 5.721 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.700 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (5.679, 5.700, 5.721), stdev = 0.021
  CI (99.9%): [5.323, 6.078] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 17.085 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.173 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.924 ±(99.9%) 0.015 ms/op
Iteration   1: 5.995 ±(99.9%) 0.019 ms/op
Iteration   2: 5.922 ±(99.9%) 0.016 ms/op
Iteration   3: 5.862 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.926 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (5.862, 5.926, 5.995), stdev = 0.067
  CI (99.9%): [4.709, 7.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 21.326 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 8.364 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 7.042 ±(99.9%) 0.017 ms/op
Iteration   1: 6.812 ±(99.9%) 0.014 ms/op
Iteration   2: 6.893 ±(99.9%) 0.019 ms/op
Iteration   3: 7.015 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.907 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (6.812, 6.907, 7.015), stdev = 0.102
  CI (99.9%): [5.039, 8.775] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 20.810 ±(99.9%) 0.357 ms/op
# Warmup Iteration   2: 7.641 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.071 ±(99.9%) 0.026 ms/op
Iteration   1: 5.740 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.122 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   7.930 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  24.258 ms/op
                 createUser·p0.9999: 30.142 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   2: 6.011 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.511 ms/op
                 createUser·p0.50:   5.743 ms/op
                 createUser·p0.90:   7.610 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   10.715 ms/op
                 createUser·p0.999:  17.465 ms/op
                 createUser·p0.9999: 31.316 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   3: 5.817 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.091 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.266 ms/op
                 createUser·p0.95:   8.223 ms/op
                 createUser·p0.99:   11.092 ms/op
                 createUser·p0.999:  28.685 ms/op
                 createUser·p0.9999: 39.649 ms/op
                 createUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163915
  mean =      5.854 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 36944 
    [ 5.000, 10.000) = 124344 
    [10.000, 15.000) = 2348 
    [15.000, 20.000) = 112 
    [20.000, 25.000) = 20 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 53 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.091 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.233 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     21.725 ms/op
     p(99.9900) =     36.323 ms/op
     p(99.9990) =     40.179 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.065 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.959 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.023 ms/op
Iteration   1: 5.720 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.283 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   11.141 ms/op
                 existUser·p0.999:  18.237 ms/op
                 existUser·p0.9999: 30.187 ms/op
                 existUser·p1.00:   30.441 ms/op

Iteration   2: 5.652 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   6.971 ms/op
                 existUser·p0.95:   8.119 ms/op
                 existUser·p0.99:   12.141 ms/op
                 existUser·p0.999:  27.572 ms/op
                 existUser·p0.9999: 34.865 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   3: 5.819 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.363 ms/op
                 existUser·p0.50:   5.472 ms/op
                 existUser·p0.90:   7.406 ms/op
                 existUser·p0.95:   8.569 ms/op
                 existUser·p0.99:   11.441 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 37.880 ms/op
                 existUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 167334
  mean =      5.729 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 50037 
    [ 5.000,  7.500) = 103310 
    [ 7.500, 10.000) = 10354 
    [10.000, 12.500) = 2628 
    [12.500, 15.000) = 644 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.479 ms/op
     p(99.9000) =     18.306 ms/op
     p(99.9900) =     35.407 ms/op
     p(99.9990) =     38.483 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:14
# Fork: 1 of 1
# Warmup Iteration   1: 18.949 ±(99.9%) 0.326 ms/op
# Warmup Iteration   2: 7.626 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.214 ±(99.9%) 0.028 ms/op
Iteration   1: 6.339 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   5.947 ms/op
                 getUser·p0.90:   8.086 ms/op
                 getUser·p0.95:   9.470 ms/op
                 getUser·p0.99:   13.614 ms/op
                 getUser·p0.999:  31.228 ms/op
                 getUser·p0.9999: 35.321 ms/op
                 getUser·p1.00:   37.945 ms/op

Iteration   2: 6.005 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   5.685 ms/op
                 getUser·p0.90:   7.545 ms/op
                 getUser·p0.95:   8.634 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  19.935 ms/op
                 getUser·p0.9999: 32.113 ms/op
                 getUser·p1.00:   32.965 ms/op

Iteration   3: 6.429 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   2.634 ms/op
                 getUser·p0.50:   5.808 ms/op
                 getUser·p0.90:   9.126 ms/op
                 getUser·p0.95:   10.502 ms/op
                 getUser·p0.99:   14.467 ms/op
                 getUser·p0.999:  31.171 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 153562
  mean =      6.252 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 23422 
    [ 5.000,  7.500) = 108614 
    [ 7.500, 10.000) = 15120 
    [10.000, 12.500) = 4240 
    [12.500, 15.000) = 1314 
    [15.000, 17.500) = 436 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 89 
    [32.500, 35.000) = 51 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      5.800 ms/op
     p(90.0000) =      8.176 ms/op
     p(95.0000) =      9.617 ms/op
     p(99.0000) =     13.392 ms/op
     p(99.9000) =     29.876 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     38.697 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 21.130 ±(99.9%) 0.375 ms/op
# Warmup Iteration   2: 9.157 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 6.996 ±(99.9%) 0.030 ms/op
Iteration   1: 7.212 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.432 ms/op
                 listUser·p0.50:   6.840 ms/op
                 listUser·p0.90:   8.978 ms/op
                 listUser·p0.95:   10.240 ms/op
                 listUser·p0.99:   13.298 ms/op
                 listUser·p0.999:  30.725 ms/op
                 listUser·p0.9999: 32.866 ms/op
                 listUser·p1.00:   35.783 ms/op

Iteration   2: 7.132 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   6.660 ms/op
                 listUser·p0.90:   9.028 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   14.565 ms/op
                 listUser·p0.999:  33.391 ms/op
                 listUser·p0.9999: 35.751 ms/op
                 listUser·p1.00:   37.552 ms/op

Iteration   3: 7.108 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.961 ms/op
                 listUser·p0.50:   6.701 ms/op
                 listUser·p0.90:   8.700 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   13.612 ms/op
                 listUser·p0.999:  30.078 ms/op
                 listUser·p0.9999: 45.777 ms/op
                 listUser·p1.00:   46.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 134184
  mean =      7.151 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1742 
    [ 5.000, 10.000) = 124770 
    [10.000, 15.000) = 6842 
    [15.000, 20.000) = 523 
    [20.000, 25.000) = 19 
    [25.000, 30.000) = 87 
    [30.000, 35.000) = 151 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.834 ms/op
     p(50.0000) =      6.734 ms/op
     p(90.0000) =      8.897 ms/op
     p(95.0000) =     10.273 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     31.654 ms/op
     p(99.9900) =     43.182 ms/op
     p(99.9990) =     46.503 ms/op
     p(99.9999) =     46.727 ms/op
    p(100.0000) =     46.727 ms/op


# Run complete. Total time: 00:13:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.311 ± 2.150  ops/ms
ClientPb.existUser                       thrpt       3   5.579 ± 3.395  ops/ms
ClientPb.getUser                         thrpt       3   5.294 ± 1.875  ops/ms
ClientPb.listUser                        thrpt       3   4.486 ± 2.345  ops/ms
ClientPb.createUser                       avgt       3   6.138 ± 3.192   ms/op
ClientPb.existUser                        avgt       3   5.700 ± 0.378   ms/op
ClientPb.getUser                          avgt       3   5.926 ± 1.217   ms/op
ClientPb.listUser                         avgt       3   6.907 ± 1.868   ms/op
ClientPb.createUser                     sample  163915   5.854 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.091           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.315           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.233           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.813           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.725           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.323           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.305           ms/op
ClientPb.existUser                      sample  167334   5.729 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.378           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.389           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.479           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.306           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.407           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.322           ms/op
ClientPb.getUser                        sample  153562   6.252 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.510           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.617           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.392           ms/op
ClientPb.getUser:getUser·p0.999         sample          29.876           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.865           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.732           ms/op
ClientPb.listUser                       sample  134184   7.151 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.834           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.734           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.273           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.779           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.654           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.182           ms/op
ClientPb.listUser:listUser·p1.00        sample          46.727           ms/op
