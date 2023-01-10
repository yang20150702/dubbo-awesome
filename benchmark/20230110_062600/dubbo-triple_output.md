# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.770 ops/ms
# Warmup Iteration   2: 3.773 ops/ms
# Warmup Iteration   3: 8.308 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 8.878 ops/ms
Iteration   3: 8.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.879 ±(99.9%) 1.016 ops/ms [Average]
  (min, avg, max) = (8.824, 8.879, 8.936), stdev = 0.056
  CI (99.9%): [7.864, 9.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.838 ops/ms
# Warmup Iteration   2: 8.326 ops/ms
# Warmup Iteration   3: 9.365 ops/ms
Iteration   1: 9.090 ops/ms
Iteration   2: 9.423 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.365 ±(99.9%) 4.581 ops/ms [Average]
  (min, avg, max) = (9.090, 9.365, 9.581), stdev = 0.251
  CI (99.9%): [4.783, 13.946] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.677 ops/ms
# Warmup Iteration   2: 8.167 ops/ms
# Warmup Iteration   3: 8.842 ops/ms
Iteration   1: 9.243 ops/ms
Iteration   2: 8.970 ops/ms
Iteration   3: 9.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.183 ±(99.9%) 3.471 ops/ms [Average]
  (min, avg, max) = (8.970, 9.183, 9.336), stdev = 0.190
  CI (99.9%): [5.712, 12.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ops/ms
# Warmup Iteration   2: 7.336 ops/ms
# Warmup Iteration   3: 7.798 ops/ms
Iteration   1: 7.559 ops/ms
Iteration   2: 7.587 ops/ms
Iteration   3: 7.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.639 ±(99.9%) 2.106 ops/ms [Average]
  (min, avg, max) = (7.559, 7.639, 7.771), stdev = 0.115
  CI (99.9%): [5.534, 9.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.607 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.009 ms/op
Iteration   1: 3.526 ±(99.9%) 0.010 ms/op
Iteration   2: 3.505 ±(99.9%) 0.006 ms/op
Iteration   3: 3.398 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.476 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (3.398, 3.476, 3.526), stdev = 0.068
  CI (99.9%): [2.227, 4.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.946 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.008 ms/op
Iteration   1: 3.430 ±(99.9%) 0.004 ms/op
Iteration   2: 3.378 ±(99.9%) 0.007 ms/op
Iteration   3: 3.349 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.386 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.349, 3.386, 3.430), stdev = 0.041
  CI (99.9%): [2.633, 4.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.007 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.004 ms/op
Iteration   1: 3.685 ±(99.9%) 0.007 ms/op
Iteration   2: 3.473 ±(99.9%) 0.005 ms/op
Iteration   3: 3.503 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.553 ±(99.9%) 2.093 ms/op [Average]
  (min, avg, max) = (3.473, 3.553, 3.685), stdev = 0.115
  CI (99.9%): [1.460, 5.647] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.482 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.011 ms/op
Iteration   1: 4.035 ±(99.9%) 0.012 ms/op
Iteration   2: 4.094 ±(99.9%) 0.007 ms/op
Iteration   3: 3.985 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.038 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (3.985, 4.038, 4.094), stdev = 0.054
  CI (99.9%): [3.048, 5.028] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.815 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.015 ms/op
Iteration   1: 3.603 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  21.799 ms/op
                 createUser·p0.9999: 24.645 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   2: 3.484 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  25.140 ms/op
                 createUser·p0.9999: 27.928 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   3: 3.516 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  24.032 ms/op
                 createUser·p0.9999: 28.370 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271725
  mean =      3.534 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4642 
    [ 2.500,  5.000) = 260228 
    [ 5.000,  7.500) = 5422 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 133 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.140 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.228 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.008 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  20.579 ms/op
                 existUser·p0.9999: 26.422 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  23.661 ms/op
                 existUser·p0.9999: 26.043 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  21.051 ms/op
                 existUser·p0.9999: 26.694 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283267
  mean =      3.389 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13625 
    [ 2.500,  5.000) = 262252 
    [ 5.000,  7.500) = 6441 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     20.897 ms/op
     p(99.9900) =     26.433 ms/op
     p(99.9990) =     27.274 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.795 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.013 ms/op
Iteration   1: 3.472 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.823 ms/op
                 getUser·p0.999:  11.827 ms/op
                 getUser·p0.9999: 25.257 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   2: 3.366 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  23.985 ms/op
                 getUser·p0.9999: 35.619 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   3: 3.477 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 34.655 ms/op
                 getUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279147
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5689 
    [ 2.500,  5.000) = 266627 
    [ 5.000,  7.500) = 5623 
    [ 7.500, 10.000) = 756 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 51 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     14.547 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     36.386 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.804 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.013 ms/op
Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.901 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  21.183 ms/op
                 listUser·p0.9999: 24.544 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   8.104 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.107 ms/op
                 listUser·p0.999:  14.905 ms/op
                 listUser·p0.9999: 26.575 ms/op
                 listUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241059
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 231409 
    [ 5.000,  7.500) = 6791 
    [ 7.500, 10.000) = 1854 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.627 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.879 ± 1.016  ops/ms
ClientPb.existUser                       thrpt       3   9.365 ± 4.581  ops/ms
ClientPb.getUser                         thrpt       3   9.183 ± 3.471  ops/ms
ClientPb.listUser                        thrpt       3   7.639 ± 2.106  ops/ms
ClientPb.createUser                       avgt       3   3.476 ± 1.249   ms/op
ClientPb.existUser                        avgt       3   3.386 ± 0.753   ms/op
ClientPb.getUser                          avgt       3   3.553 ± 2.093   ms/op
ClientPb.listUser                         avgt       3   4.038 ± 0.990   ms/op
ClientPb.createUser                     sample  271725   3.534 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.038           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.381           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.951           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  283267   3.389 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.061           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.897           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.433           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  279147   3.437 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.315           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.547           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.865           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  241059   3.981 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.440           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.707           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
