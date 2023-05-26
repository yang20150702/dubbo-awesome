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
# Warmup Iteration   1: 2.345 ops/ms
# Warmup Iteration   2: 6.226 ops/ms
# Warmup Iteration   3: 8.701 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.525 ops/ms
Iteration   3: 9.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.368 ±(99.9%) 3.029 ops/ms [Average]
  (min, avg, max) = (9.194, 9.368, 9.525), stdev = 0.166
  CI (99.9%): [6.339, 12.397] (assumes normal distribution)


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
# Warmup Iteration   1: 3.059 ops/ms
# Warmup Iteration   2: 8.897 ops/ms
# Warmup Iteration   3: 9.684 ops/ms
Iteration   1: 10.079 ops/ms
Iteration   2: 9.575 ops/ms
Iteration   3: 9.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.741 ±(99.9%) 5.328 ops/ms [Average]
  (min, avg, max) = (9.570, 9.741, 10.079), stdev = 0.292
  CI (99.9%): [4.413, 15.069] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.526 ops/ms
# Warmup Iteration   2: 8.595 ops/ms
# Warmup Iteration   3: 9.168 ops/ms
Iteration   1: 9.537 ops/ms
Iteration   2: 9.412 ops/ms
Iteration   3: 9.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.438 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (9.365, 9.438, 9.537), stdev = 0.089
  CI (99.9%): [7.813, 11.064] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.838 ops/ms
# Warmup Iteration   2: 7.090 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.104 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.109 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (7.964, 8.109, 8.259), stdev = 0.147
  CI (99.9%): [5.419, 10.799] (assumes normal distribution)


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
# Warmup Iteration   1: 10.273 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.503 ±(99.9%) 0.008 ms/op
Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
Iteration   3: 3.323 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.390 ±(99.9%) 1.787 ms/op [Average]
  (min, avg, max) = (3.323, 3.390, 3.503), stdev = 0.098
  CI (99.9%): [1.603, 5.177] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.707 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.005 ms/op
Iteration   1: 3.183 ±(99.9%) 0.008 ms/op
Iteration   2: 3.289 ±(99.9%) 0.006 ms/op
Iteration   3: 3.192 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.221 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.183, 3.221, 3.289), stdev = 0.059
  CI (99.9%): [2.148, 4.294] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.948 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.006 ms/op
Iteration   1: 3.489 ±(99.9%) 0.005 ms/op
Iteration   2: 3.296 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.383 ±(99.9%) 1.790 ms/op [Average]
  (min, avg, max) = (3.296, 3.383, 3.489), stdev = 0.098
  CI (99.9%): [1.593, 5.173] (assumes normal distribution)


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
# Warmup Iteration   1: 10.331 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.008 ms/op
Iteration   1: 4.019 ±(99.9%) 0.007 ms/op
Iteration   2: 3.982 ±(99.9%) 0.007 ms/op
Iteration   3: 3.912 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.971 ±(99.9%) 0.998 ms/op [Average]
  (min, avg, max) = (3.912, 3.971, 4.019), stdev = 0.055
  CI (99.9%): [2.973, 4.969] (assumes normal distribution)


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
# Warmup Iteration   1: 8.610 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  16.250 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  11.180 ms/op
                 createUser·p0.9999: 26.429 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   3: 3.296 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  12.583 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290476
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19285 
    [ 2.500,  5.000) = 264702 
    [ 5.000,  7.500) = 5573 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     13.640 ms/op
     p(99.9900) =     25.328 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 7.770 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.817 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  11.628 ms/op
                 existUser·p0.9999: 25.991 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 31.097 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 3.250 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  9.214 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294535
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8163 
    [ 2.500,  5.000) = 280880 
    [ 5.000,  7.500) = 4646 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     10.925 ms/op
     p(99.9900) =     29.286 ms/op
     p(99.9990) =     31.430 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 8.540 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.010 ms/op
Iteration   1: 3.375 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  21.627 ms/op
                 getUser·p0.9999: 26.958 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   2: 3.422 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.604 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.164 ms/op
                 getUser·p0.999:  26.009 ms/op
                 getUser·p0.9999: 29.185 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  18.476 ms/op
                 getUser·p0.9999: 26.711 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280303
  mean =      3.423 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13984 
    [ 2.500,  5.000) = 259253 
    [ 5.000,  7.500) = 5912 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     19.018 ms/op
     p(99.9900) =     28.538 ms/op
     p(99.9990) =     29.935 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 11.408 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.013 ms/op
Iteration   1: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  19.599 ms/op
                 listUser·p0.9999: 22.213 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.156 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  16.645 ms/op
                 listUser·p0.9999: 20.358 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 3.996 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237634
  mean =      4.039 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 228934 
    [ 5.000,  7.500) = 5686 
    [ 7.500, 10.000) = 2221 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     21.930 ms/op
     p(99.9990) =     22.716 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.368 ± 3.029  ops/ms
ClientPb.existUser                       thrpt       3   9.741 ± 5.328  ops/ms
ClientPb.getUser                         thrpt       3   9.438 ± 1.625  ops/ms
ClientPb.listUser                        thrpt       3   8.109 ± 2.690  ops/ms
ClientPb.createUser                       avgt       3   3.390 ± 1.787   ms/op
ClientPb.existUser                        avgt       3   3.221 ± 1.073   ms/op
ClientPb.getUser                          avgt       3   3.383 ± 1.790   ms/op
ClientPb.listUser                         avgt       3   3.971 ± 0.998   ms/op
ClientPb.createUser                     sample  290476   3.305 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.640           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.328           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.001           ms/op
ClientPb.existUser                      sample  294535   3.255 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.358           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.931           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.925           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.286           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.654           ms/op
ClientPb.getUser                        sample  280303   3.423 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.018           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.538           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.671           ms/op
ClientPb.listUser                       sample  237634   4.039 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.367           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.930           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.741           ms/op
