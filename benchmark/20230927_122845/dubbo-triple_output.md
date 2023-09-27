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
# Warmup Iteration   1: 1.950 ops/ms
# Warmup Iteration   2: 5.153 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 8.702 ops/ms
Iteration   2: 9.086 ops/ms
Iteration   3: 9.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.979 ±(99.9%) 4.413 ops/ms [Average]
  (min, avg, max) = (8.702, 8.979, 9.149), stdev = 0.242
  CI (99.9%): [4.566, 13.392] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.502 ops/ms
# Warmup Iteration   2: 8.257 ops/ms
# Warmup Iteration   3: 9.449 ops/ms
Iteration   1: 9.376 ops/ms
Iteration   2: 9.572 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.439 ±(99.9%) 2.087 ops/ms [Average]
  (min, avg, max) = (9.371, 9.439, 9.572), stdev = 0.114
  CI (99.9%): [7.352, 11.527] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 8.508 ops/ms
# Warmup Iteration   3: 8.840 ops/ms
Iteration   1: 9.151 ops/ms
Iteration   2: 9.231 ops/ms
Iteration   3: 9.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.165 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (9.113, 9.165, 9.231), stdev = 0.060
  CI (99.9%): [8.068, 10.262] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 6.963 ops/ms
# Warmup Iteration   3: 7.217 ops/ms
Iteration   1: 7.624 ops/ms
Iteration   2: 7.573 ops/ms
Iteration   3: 7.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.637 ±(99.9%) 1.318 ops/ms [Average]
  (min, avg, max) = (7.573, 7.637, 7.716), stdev = 0.072
  CI (99.9%): [6.319, 8.956] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.015 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.005 ms/op
Iteration   1: 3.545 ±(99.9%) 0.006 ms/op
Iteration   2: 3.459 ±(99.9%) 0.006 ms/op
Iteration   3: 3.546 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.517 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.459, 3.517, 3.546), stdev = 0.050
  CI (99.9%): [2.606, 4.427] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.949 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.006 ms/op
Iteration   1: 3.358 ±(99.9%) 0.004 ms/op
Iteration   2: 3.336 ±(99.9%) 0.006 ms/op
Iteration   3: 3.376 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.357 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (3.336, 3.357, 3.376), stdev = 0.020
  CI (99.9%): [2.983, 3.730] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.156 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.002 ms/op
Iteration   1: 3.575 ±(99.9%) 0.003 ms/op
Iteration   2: 3.510 ±(99.9%) 0.005 ms/op
Iteration   3: 3.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.517 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.467, 3.517, 3.575), stdev = 0.054
  CI (99.9%): [2.524, 4.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.650 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.006 ms/op
Iteration   1: 4.207 ±(99.9%) 0.007 ms/op
Iteration   2: 4.074 ±(99.9%) 0.006 ms/op
Iteration   3: 4.214 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.165 ±(99.9%) 1.433 ms/op [Average]
  (min, avg, max) = (4.074, 4.165, 4.214), stdev = 0.079
  CI (99.9%): [2.732, 5.598] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.820 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.018 ms/op
Iteration   1: 3.492 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  21.451 ms/op
                 createUser·p0.9999: 32.003 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   2: 3.576 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 26.247 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.487 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  19.542 ms/op
                 createUser·p0.9999: 27.225 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272737
  mean =      3.518 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5834 
    [ 2.500,  5.000) = 258476 
    [ 5.000,  7.500) = 6935 
    [ 7.500, 10.000) = 817 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.133 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
Iteration   1: 3.405 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  19.794 ms/op
                 existUser·p0.9999: 22.780 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.334 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.769 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  21.168 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.506 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.307 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.479 ms/op
                 existUser·p0.999:  14.638 ms/op
                 existUser·p0.9999: 27.914 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281296
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7640 
    [ 2.500,  5.000) = 264750 
    [ 5.000,  7.500) = 7276 
    [ 7.500, 10.000) = 1004 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     18.078 ms/op
     p(99.9900) =     26.468 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.404 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
Iteration   1: 3.587 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 24.912 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   2: 3.519 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  19.528 ms/op
                 getUser·p0.9999: 22.374 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.493 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  21.019 ms/op
                 getUser·p0.9999: 27.024 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271703
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3414 
    [ 2.500,  5.000) = 258440 
    [ 5.000,  7.500) = 6822 
    [ 7.500, 10.000) = 2146 
    [10.000, 12.500) = 422 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.667 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     25.542 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.692 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.017 ms/op
Iteration   1: 4.262 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.080 ms/op
                 listUser·p0.999:  23.036 ms/op
                 listUser·p0.9999: 32.357 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   2: 4.198 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 4.176 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  15.423 ms/op
                 listUser·p0.9999: 18.263 ms/op
                 listUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227898
  mean =      4.212 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 213723 
    [ 5.000,  7.500) = 10455 
    [ 7.500, 10.000) = 2647 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     15.992 ms/op
     p(99.9900) =     29.344 ms/op
     p(99.9990) =     34.126 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.979 ± 4.413  ops/ms
ClientPb.existUser                       thrpt       3   9.439 ± 2.087  ops/ms
ClientPb.getUser                         thrpt       3   9.165 ± 1.097  ops/ms
ClientPb.listUser                        thrpt       3   7.637 ± 1.318  ops/ms
ClientPb.createUser                       avgt       3   3.517 ± 0.910   ms/op
ClientPb.existUser                        avgt       3   3.357 ± 0.373   ms/op
ClientPb.getUser                          avgt       3   3.517 ± 0.994   ms/op
ClientPb.listUser                         avgt       3   4.165 ± 1.433   ms/op
ClientPb.createUser                     sample  272737   3.518 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.660           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.168           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.230           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.834           ms/op
ClientPb.existUser                      sample  281296   3.414 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.307           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.468           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  271703   3.532 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.667           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.694           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.542           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  227898   4.212 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.992           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.341           ms/op
