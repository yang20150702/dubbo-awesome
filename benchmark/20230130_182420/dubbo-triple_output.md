# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.033 ops/ms
# Warmup Iteration   2: 5.652 ops/ms
# Warmup Iteration   3: 8.544 ops/ms
Iteration   1: 9.253 ops/ms
Iteration   2: 9.243 ops/ms
Iteration   3: 9.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.286 ±(99.9%) 1.208 ops/ms [Average]
  (min, avg, max) = (9.243, 9.286, 9.362), stdev = 0.066
  CI (99.9%): [8.078, 10.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ops/ms
# Warmup Iteration   2: 8.399 ops/ms
# Warmup Iteration   3: 9.254 ops/ms
Iteration   1: 9.703 ops/ms
Iteration   2: 9.456 ops/ms
Iteration   3: 9.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.527 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (9.423, 9.527, 9.703), stdev = 0.153
  CI (99.9%): [6.737, 12.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.816 ops/ms
# Warmup Iteration   2: 8.600 ops/ms
# Warmup Iteration   3: 8.910 ops/ms
Iteration   1: 9.500 ops/ms
Iteration   2: 9.226 ops/ms
Iteration   3: 9.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.308 ±(99.9%) 3.044 ops/ms [Average]
  (min, avg, max) = (9.199, 9.308, 9.500), stdev = 0.167
  CI (99.9%): [6.265, 12.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.651 ops/ms
# Warmup Iteration   2: 6.924 ops/ms
# Warmup Iteration   3: 7.556 ops/ms
Iteration   1: 8.091 ops/ms
Iteration   2: 7.862 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.006 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (7.862, 8.006, 8.091), stdev = 0.126
  CI (99.9%): [5.716, 10.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.256 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.004 ms/op
Iteration   1: 3.489 ±(99.9%) 0.007 ms/op
Iteration   2: 3.471 ±(99.9%) 0.005 ms/op
Iteration   3: 3.444 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.468 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (3.444, 3.468, 3.489), stdev = 0.022
  CI (99.9%): [3.060, 3.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.678 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.004 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
Iteration   2: 3.382 ±(99.9%) 0.004 ms/op
Iteration   3: 3.238 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.287 ±(99.9%) 1.511 ms/op [Average]
  (min, avg, max) = (3.238, 3.287, 3.382), stdev = 0.083
  CI (99.9%): [1.776, 4.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.905 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.003 ms/op
Iteration   1: 3.433 ±(99.9%) 0.005 ms/op
Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
Iteration   3: 3.510 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.433, 3.483, 3.510), stdev = 0.043
  CI (99.9%): [2.690, 4.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.147 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.575 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.010 ms/op
Iteration   1: 4.222 ±(99.9%) 0.007 ms/op
Iteration   2: 4.055 ±(99.9%) 0.014 ms/op
Iteration   3: 3.939 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.072 ±(99.9%) 2.600 ms/op [Average]
  (min, avg, max) = (3.939, 4.072, 4.222), stdev = 0.142
  CI (99.9%): [1.472, 6.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.922 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
Iteration   1: 3.451 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  20.644 ms/op
                 createUser·p0.9999: 24.123 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 3.498 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  24.101 ms/op
                 createUser·p0.9999: 31.710 ms/op
                 createUser·p1.00:   32.768 ms/op

Iteration   3: 3.462 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  21.057 ms/op
                 createUser·p0.9999: 33.489 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276628
  mean =      3.470 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5297 
    [ 2.500,  5.000) = 264090 
    [ 5.000,  7.500) = 6271 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     21.541 ms/op
     p(99.9900) =     32.703 ms/op
     p(99.9990) =     33.701 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.438 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.009 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 25.200 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 3.287 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  14.287 ms/op
                 existUser·p0.9999: 28.028 ms/op
                 existUser·p1.00:   29.786 ms/op

Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  21.581 ms/op
                 existUser·p0.9999: 27.591 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288429
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11955 
    [ 2.500,  5.000) = 270897 
    [ 5.000,  7.500) = 4279 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 131 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     28.433 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.303 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.011 ms/op
Iteration   1: 3.487 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  12.850 ms/op
                 getUser·p0.9999: 22.894 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.450 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   6.262 ms/op
                 getUser·p0.999:  22.447 ms/op
                 getUser·p0.9999: 31.505 ms/op
                 getUser·p1.00:   32.211 ms/op

Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 27.873 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278063
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3833 
    [ 2.500,  5.000) = 266353 
    [ 5.000,  7.500) = 6550 
    [ 7.500, 10.000) = 773 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     13.646 ms/op
     p(99.9900) =     30.854 ms/op
     p(99.9990) =     31.759 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.280 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.013 ms/op
Iteration   1: 4.174 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  22.033 ms/op
                 listUser·p0.9999: 24.883 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 4.025 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  16.505 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  15.242 ms/op
                 listUser·p0.9999: 19.631 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236094
  mean =      4.067 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 226017 
    [ 5.000,  7.500) = 7331 
    [ 7.500, 10.000) = 1841 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     24.261 ms/op
     p(99.9990) =     25.142 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.286 ± 1.208  ops/ms
ClientPb.existUser                       thrpt       3   9.527 ± 2.790  ops/ms
ClientPb.getUser                         thrpt       3   9.308 ± 3.044  ops/ms
ClientPb.listUser                        thrpt       3   8.006 ± 2.290  ops/ms
ClientPb.createUser                       avgt       3   3.468 ± 0.408   ms/op
ClientPb.existUser                        avgt       3   3.287 ± 1.511   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 0.793   ms/op
ClientPb.listUser                         avgt       3   4.072 ± 2.600   ms/op
ClientPb.createUser                     sample  276628   3.470 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.118           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.481           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.541           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.703           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  288429   3.325 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.835           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.197           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.786           ms/op
ClientPb.getUser                        sample  278063   3.452 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.646           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.854           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.211           ms/op
ClientPb.listUser                       sample  236094   4.067 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.288           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.261           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
