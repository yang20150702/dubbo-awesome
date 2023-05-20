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
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 5.862 ops/ms
# Warmup Iteration   3: 9.087 ops/ms
Iteration   1: 9.481 ops/ms
Iteration   2: 9.518 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.636 ±(99.9%) 4.325 ops/ms [Average]
  (min, avg, max) = (9.481, 9.636, 9.909), stdev = 0.237
  CI (99.9%): [5.311, 13.961] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ops/ms
# Warmup Iteration   2: 9.681 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.259 ops/ms
Iteration   2: 10.211 ops/ms
Iteration   3: 10.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.338 ±(99.9%) 3.292 ops/ms [Average]
  (min, avg, max) = (10.211, 10.338, 10.545), stdev = 0.180
  CI (99.9%): [7.046, 13.631] (assumes normal distribution)


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
# Warmup Iteration   1: 3.256 ops/ms
# Warmup Iteration   2: 9.344 ops/ms
# Warmup Iteration   3: 9.834 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 9.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.209 ±(99.9%) 4.720 ops/ms [Average]
  (min, avg, max) = (9.911, 10.209, 10.366), stdev = 0.259
  CI (99.9%): [5.490, 14.929] (assumes normal distribution)


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
# Warmup Iteration   1: 3.207 ops/ms
# Warmup Iteration   2: 7.554 ops/ms
# Warmup Iteration   3: 8.291 ops/ms
Iteration   1: 8.363 ops/ms
Iteration   2: 8.459 ops/ms
Iteration   3: 8.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.443 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (8.363, 8.443, 8.508), stdev = 0.074
  CI (99.9%): [7.094, 9.793] (assumes normal distribution)


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
# Warmup Iteration   1: 7.979 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.004 ms/op
Iteration   1: 3.178 ±(99.9%) 0.010 ms/op
Iteration   2: 3.262 ±(99.9%) 0.006 ms/op
Iteration   3: 3.177 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.206 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (3.177, 3.206, 3.262), stdev = 0.049
  CI (99.9%): [2.315, 4.097] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.975 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.006 ms/op
Iteration   1: 3.093 ±(99.9%) 0.009 ms/op
Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
Iteration   3: 3.142 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.087 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.027, 3.087, 3.142), stdev = 0.058
  CI (99.9%): [2.033, 4.141] (assumes normal distribution)


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
# Warmup Iteration   1: 8.068 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.006 ms/op
Iteration   1: 3.242 ±(99.9%) 0.005 ms/op
Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
Iteration   3: 3.132 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.165 ±(99.9%) 1.232 ms/op [Average]
  (min, avg, max) = (3.120, 3.165, 3.242), stdev = 0.068
  CI (99.9%): [1.933, 4.396] (assumes normal distribution)


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
# Warmup Iteration   1: 9.264 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.008 ms/op
Iteration   1: 3.842 ±(99.9%) 0.008 ms/op
Iteration   2: 3.808 ±(99.9%) 0.007 ms/op
Iteration   3: 3.846 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.832 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (3.808, 3.832, 3.846), stdev = 0.021
  CI (99.9%): [3.454, 4.210] (assumes normal distribution)


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
# Warmup Iteration   1: 7.912 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.009 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  19.028 ms/op
                 createUser·p0.9999: 23.178 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   2: 3.195 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.733 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  13.174 ms/op
                 createUser·p0.9999: 34.151 ms/op
                 createUser·p1.00:   35.783 ms/op

Iteration   3: 3.205 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  17.021 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300987
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30597 
    [ 2.500,  5.000) = 265201 
    [ 5.000,  7.500) = 4294 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     32.368 ms/op
     p(99.9990) =     35.520 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 7.422 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 23.094 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.703 ms/op
                 existUser·p0.9999: 20.791 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.853 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  10.512 ms/op
                 existUser·p0.9999: 25.708 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308465
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31892 
    [ 2.500,  5.000) = 272206 
    [ 5.000,  7.500) = 3745 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      9.741 ms/op
     p(99.9900) =     24.689 ms/op
     p(99.9990) =     26.132 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 8.398 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
Iteration   1: 3.336 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  18.289 ms/op
                 getUser·p0.9999: 24.950 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 3.237 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  13.140 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  16.885 ms/op
                 getUser·p0.9999: 28.558 ms/op
                 getUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289307
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15817 
    [ 2.500,  5.000) = 267148 
    [ 5.000,  7.500) = 5238 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     26.678 ms/op
     p(99.9990) =     28.912 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 9.010 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.012 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.859 ms/op
                 listUser·p0.999:  15.611 ms/op
                 listUser·p0.9999: 21.078 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.847 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.276 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 18.111 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.864 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.109 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250039
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 241139 
    [ 5.000,  7.500) = 6429 
    [ 7.500, 10.000) = 1751 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     14.921 ms/op
     p(99.9900) =     20.479 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.636 ± 4.325  ops/ms
ClientPb.existUser                       thrpt       3  10.338 ± 3.292  ops/ms
ClientPb.getUser                         thrpt       3  10.209 ± 4.720  ops/ms
ClientPb.listUser                        thrpt       3   8.443 ± 1.349  ops/ms
ClientPb.createUser                       avgt       3   3.206 ± 0.891   ms/op
ClientPb.existUser                        avgt       3   3.087 ± 1.054   ms/op
ClientPb.getUser                          avgt       3   3.165 ± 1.232   ms/op
ClientPb.listUser                         avgt       3   3.832 ± 0.378   ms/op
ClientPb.createUser                     sample  300987   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.514           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.368           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  308465   3.109 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.354           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.741           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.689           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.804           ms/op
ClientPb.getUser                        sample  289307   3.317 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.182           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.189           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.678           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.131           ms/op
ClientPb.listUser                       sample  250039   3.837 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.655           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.921           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.479           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.249           ms/op
