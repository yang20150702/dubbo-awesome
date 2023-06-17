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
# Warmup Iteration   1: 2.158 ops/ms
# Warmup Iteration   2: 5.699 ops/ms
# Warmup Iteration   3: 8.267 ops/ms
Iteration   1: 9.270 ops/ms
Iteration   2: 9.095 ops/ms
Iteration   3: 8.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.060 ±(99.9%) 4.181 ops/ms [Average]
  (min, avg, max) = (8.815, 9.060, 9.270), stdev = 0.229
  CI (99.9%): [4.879, 13.241] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.765 ops/ms
# Warmup Iteration   2: 8.479 ops/ms
# Warmup Iteration   3: 9.530 ops/ms
Iteration   1: 9.208 ops/ms
Iteration   2: 9.272 ops/ms
Iteration   3: 9.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.403 ±(99.9%) 5.197 ops/ms [Average]
  (min, avg, max) = (9.208, 9.403, 9.730), stdev = 0.285
  CI (99.9%): [4.207, 14.600] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.622 ops/ms
# Warmup Iteration   2: 8.347 ops/ms
# Warmup Iteration   3: 8.835 ops/ms
Iteration   1: 9.467 ops/ms
Iteration   2: 9.386 ops/ms
Iteration   3: 9.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.500 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (9.386, 9.500, 9.648), stdev = 0.134
  CI (99.9%): [7.052, 11.948] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.751 ops/ms
# Warmup Iteration   2: 7.412 ops/ms
# Warmup Iteration   3: 7.856 ops/ms
Iteration   1: 8.203 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.143 ±(99.9%) 1.063 ops/ms [Average]
  (min, avg, max) = (8.087, 8.143, 8.203), stdev = 0.058
  CI (99.9%): [7.080, 9.206] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.691 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.006 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
Iteration   2: 3.389 ±(99.9%) 0.011 ms/op
Iteration   3: 3.408 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.396 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (3.389, 3.396, 3.408), stdev = 0.011
  CI (99.9%): [3.198, 3.593] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.837 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.004 ms/op
Iteration   1: 3.338 ±(99.9%) 0.005 ms/op
Iteration   2: 3.326 ±(99.9%) 0.011 ms/op
Iteration   3: 3.374 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.346 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.326, 3.346, 3.374), stdev = 0.025
  CI (99.9%): [2.890, 3.801] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.309 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.004 ms/op
Iteration   1: 3.575 ±(99.9%) 0.006 ms/op
Iteration   2: 3.404 ±(99.9%) 0.006 ms/op
Iteration   3: 3.420 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.466 ±(99.9%) 1.726 ms/op [Average]
  (min, avg, max) = (3.404, 3.466, 3.575), stdev = 0.095
  CI (99.9%): [1.741, 5.192] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.076 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.008 ms/op
Iteration   1: 4.019 ±(99.9%) 0.010 ms/op
Iteration   2: 3.906 ±(99.9%) 0.013 ms/op
Iteration   3: 3.937 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.954 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (3.906, 3.954, 4.019), stdev = 0.059
  CI (99.9%): [2.882, 5.026] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.942 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.011 ms/op
Iteration   1: 3.447 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 22.361 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  19.924 ms/op
                 createUser·p0.9999: 22.925 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.422 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  24.378 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280420
  mean =      3.424 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8453 
    [ 2.500,  5.000) = 266097 
    [ 5.000,  7.500) = 4750 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     31.456 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.715 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
Iteration   1: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  20.488 ms/op
                 existUser·p0.9999: 22.598 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  23.080 ms/op
                 existUser·p0.9999: 28.995 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   3: 3.385 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  21.938 ms/op
                 existUser·p0.9999: 27.937 ms/op
                 existUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283756
  mean =      3.381 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8889 
    [ 2.500,  5.000) = 267176 
    [ 5.000,  7.500) = 6365 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     20.537 ms/op
     p(99.9900) =     27.906 ms/op
     p(99.9990) =     29.704 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 8.958 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.012 ms/op
Iteration   1: 3.402 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  12.845 ms/op
                 getUser·p0.9999: 24.727 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 3.455 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  23.133 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  23.219 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278950
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5921 
    [ 2.500,  5.000) = 265456 
    [ 5.000,  7.500) = 6269 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 157 
    [25.000, 27.500) = 95 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.441 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 10.835 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.014 ms/op
Iteration   1: 4.045 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.400 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  19.883 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  17.154 ms/op
                 listUser·p0.9999: 18.739 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238915
  mean =      4.016 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 584 
    [ 2.500,  5.000) = 223978 
    [ 5.000,  7.500) = 11861 
    [ 7.500, 10.000) = 1747 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 265 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     16.680 ms/op
     p(99.9900) =     21.401 ms/op
     p(99.9990) =     22.257 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.060 ± 4.181  ops/ms
ClientPb.existUser                       thrpt       3   9.403 ± 5.197  ops/ms
ClientPb.getUser                         thrpt       3   9.500 ± 2.448  ops/ms
ClientPb.listUser                        thrpt       3   8.143 ± 1.063  ops/ms
ClientPb.createUser                       avgt       3   3.396 ± 0.197   ms/op
ClientPb.existUser                        avgt       3   3.346 ± 0.455   ms/op
ClientPb.getUser                          avgt       3   3.466 ± 1.726   ms/op
ClientPb.listUser                         avgt       3   3.954 ± 1.072   ms/op
ClientPb.createUser                     sample  280420   3.424 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.397           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.366           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.456           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  283756   3.381 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.537           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.906           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.819           ms/op
ClientPb.getUser                        sample  278950   3.441 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.042           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.083           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.525           ms/op
ClientPb.listUser                       sample  238915   4.016 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.401           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.348           ms/op
