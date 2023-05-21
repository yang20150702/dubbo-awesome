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
# Warmup Iteration   1: 2.013 ops/ms
# Warmup Iteration   2: 5.703 ops/ms
# Warmup Iteration   3: 8.724 ops/ms
Iteration   1: 9.206 ops/ms
Iteration   2: 9.431 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.334 ±(99.9%) 2.107 ops/ms [Average]
  (min, avg, max) = (9.206, 9.334, 9.431), stdev = 0.116
  CI (99.9%): [7.226, 11.441] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.228 ops/ms
# Warmup Iteration   2: 9.005 ops/ms
# Warmup Iteration   3: 9.283 ops/ms
Iteration   1: 10.148 ops/ms
Iteration   2: 10.007 ops/ms
Iteration   3: 9.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.034 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (9.947, 10.034, 10.148), stdev = 0.103
  CI (99.9%): [8.147, 11.921] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 8.721 ops/ms
# Warmup Iteration   3: 9.440 ops/ms
Iteration   1: 9.513 ops/ms
Iteration   2: 9.384 ops/ms
Iteration   3: 9.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.505 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (9.384, 9.505, 9.618), stdev = 0.117
  CI (99.9%): [7.365, 11.645] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.918 ops/ms
# Warmup Iteration   2: 6.678 ops/ms
# Warmup Iteration   3: 7.664 ops/ms
Iteration   1: 7.967 ops/ms
Iteration   2: 8.143 ops/ms
Iteration   3: 7.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.981 ±(99.9%) 2.834 ops/ms [Average]
  (min, avg, max) = (7.833, 7.981, 8.143), stdev = 0.155
  CI (99.9%): [5.147, 10.815] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.103 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.005 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
Iteration   2: 3.378 ±(99.9%) 0.004 ms/op
Iteration   3: 3.333 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.340 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.310, 3.340, 3.378), stdev = 0.035
  CI (99.9%): [2.706, 3.974] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.977 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.003 ms/op
Iteration   1: 3.188 ±(99.9%) 0.003 ms/op
Iteration   2: 3.227 ±(99.9%) 0.009 ms/op
Iteration   3: 3.260 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.225 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.188, 3.225, 3.260), stdev = 0.036
  CI (99.9%): [2.567, 3.883] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.622 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.007 ms/op
Iteration   1: 3.367 ±(99.9%) 0.009 ms/op
Iteration   2: 3.334 ±(99.9%) 0.004 ms/op
Iteration   3: 3.378 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.360 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (3.334, 3.360, 3.378), stdev = 0.023
  CI (99.9%): [2.942, 3.777] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.629 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.008 ms/op
Iteration   1: 3.975 ±(99.9%) 0.009 ms/op
Iteration   2: 4.049 ±(99.9%) 0.010 ms/op
Iteration   3: 3.956 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.993 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.956, 3.993, 4.049), stdev = 0.049
  CI (99.9%): [3.093, 4.894] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.335 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
Iteration   1: 3.444 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  19.073 ms/op
                 createUser·p0.9999: 21.808 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.321 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  19.014 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  14.942 ms/op
                 createUser·p0.9999: 26.452 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280716
  mean =      3.418 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13976 
    [ 2.500,  5.000) = 260110 
    [ 5.000,  7.500) = 5686 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.038 ms/op
     p(99.9900) =     25.786 ms/op
     p(99.9990) =     27.089 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.486 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
Iteration   1: 3.189 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.525 ms/op
                 existUser·p0.999:  10.285 ms/op
                 existUser·p0.9999: 22.277 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 26.654 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.524 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  19.207 ms/op
                 existUser·p0.9999: 26.277 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286849
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16446 
    [ 2.500,  5.000) = 263450 
    [ 5.000,  7.500) = 6022 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     26.225 ms/op
     p(99.9990) =     27.494 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.911 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.081 ms/op
                 getUser·p0.999:  18.424 ms/op
                 getUser·p0.9999: 25.698 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   2: 3.437 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  21.402 ms/op
                 getUser·p0.9999: 26.477 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.430 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.052 ms/op
                 getUser·p0.999:  18.122 ms/op
                 getUser·p0.9999: 30.409 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280141
  mean =      3.424 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12934 
    [ 2.500,  5.000) = 258898 
    [ 5.000,  7.500) = 7140 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.749 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.453 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.013 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  20.455 ms/op
                 listUser·p0.9999: 24.216 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   2: 4.040 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 18.026 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 4.014 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.736 ms/op
                 listUser·p0.99:   7.394 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239823
  mean =      3.999 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 232877 
    [ 5.000,  7.500) = 4980 
    [ 7.500, 10.000) = 1155 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.746 ms/op
     p(99.9900) =     23.299 ms/op
     p(99.9990) =     25.546 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.334 ± 2.107  ops/ms
ClientPb.existUser                       thrpt       3  10.034 ± 1.887  ops/ms
ClientPb.getUser                         thrpt       3   9.505 ± 2.140  ops/ms
ClientPb.listUser                        thrpt       3   7.981 ± 2.834  ops/ms
ClientPb.createUser                       avgt       3   3.340 ± 0.634   ms/op
ClientPb.existUser                        avgt       3   3.225 ± 0.658   ms/op
ClientPb.getUser                          avgt       3   3.360 ± 0.418   ms/op
ClientPb.listUser                         avgt       3   3.993 ± 0.900   ms/op
ClientPb.createUser                     sample  280716   3.418 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.145           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.786           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.820           ms/op
ClientPb.existUser                      sample  286849   3.347 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.982           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.796           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.225           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.853           ms/op
ClientPb.getUser                        sample  280141   3.424 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.251           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.153           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.639           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.835           ms/op
ClientPb.listUser                       sample  239823   3.999 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.354           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.299           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
