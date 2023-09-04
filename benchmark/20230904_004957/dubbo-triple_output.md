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
# Warmup Iteration   1: 0.964 ops/ms
# Warmup Iteration   2: 1.919 ops/ms
# Warmup Iteration   3: 4.433 ops/ms
Iteration   1: 5.422 ops/ms
Iteration   2: 5.492 ops/ms
Iteration   3: 5.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.493 ±(99.9%) 1.308 ops/ms [Average]
  (min, avg, max) = (5.422, 5.493, 5.565), stdev = 0.072
  CI (99.9%): [4.185, 6.801] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.521 ops/ms
# Warmup Iteration   2: 4.641 ops/ms
# Warmup Iteration   3: 5.856 ops/ms
Iteration   1: 6.010 ops/ms
Iteration   2: 5.816 ops/ms
Iteration   3: 5.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.939 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (5.816, 5.939, 6.010), stdev = 0.107
  CI (99.9%): [3.989, 7.889] (assumes normal distribution)


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
# Warmup Iteration   1: 1.533 ops/ms
# Warmup Iteration   2: 4.332 ops/ms
# Warmup Iteration   3: 5.432 ops/ms
Iteration   1: 5.561 ops/ms
Iteration   2: 5.719 ops/ms
Iteration   3: 5.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.725 ±(99.9%) 3.049 ops/ms [Average]
  (min, avg, max) = (5.561, 5.725, 5.895), stdev = 0.167
  CI (99.9%): [2.676, 8.774] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.517 ops/ms
# Warmup Iteration   2: 3.566 ops/ms
# Warmup Iteration   3: 4.917 ops/ms
Iteration   1: 5.006 ops/ms
Iteration   2: 4.978 ops/ms
Iteration   3: 4.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.972 ±(99.9%) 0.662 ops/ms [Average]
  (min, avg, max) = (4.934, 4.972, 5.006), stdev = 0.036
  CI (99.9%): [4.310, 5.635] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.510 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.353 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.004 ±(99.9%) 0.011 ms/op
Iteration   1: 5.484 ±(99.9%) 0.021 ms/op
Iteration   2: 5.592 ±(99.9%) 0.011 ms/op
Iteration   3: 5.524 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.534 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (5.484, 5.534, 5.592), stdev = 0.055
  CI (99.9%): [4.534, 6.533] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.201 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.313 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.424 ±(99.9%) 0.008 ms/op
Iteration   1: 5.348 ±(99.9%) 0.007 ms/op
Iteration   2: 5.290 ±(99.9%) 0.009 ms/op
Iteration   3: 5.182 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.274 ±(99.9%) 1.538 ms/op [Average]
  (min, avg, max) = (5.182, 5.274, 5.348), stdev = 0.084
  CI (99.9%): [3.736, 6.812] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.669 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.907 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.329 ±(99.9%) 0.010 ms/op
Iteration   1: 5.216 ±(99.9%) 0.009 ms/op
Iteration   2: 5.360 ±(99.9%) 0.011 ms/op
Iteration   3: 5.310 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.295 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (5.216, 5.295, 5.360), stdev = 0.073
  CI (99.9%): [3.959, 6.632] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.602 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 7.331 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.598 ±(99.9%) 0.020 ms/op
Iteration   1: 6.397 ±(99.9%) 0.014 ms/op
Iteration   2: 6.326 ±(99.9%) 0.014 ms/op
Iteration   3: 6.300 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.341 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (6.300, 6.341, 6.397), stdev = 0.050
  CI (99.9%): [5.427, 7.255] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.142 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 7.126 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.051 ±(99.9%) 0.032 ms/op
Iteration   1: 5.530 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   7.168 ms/op
                 createUser·p0.95:   8.307 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  26.384 ms/op
                 createUser·p0.9999: 31.006 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 5.344 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.664 ms/op
                 createUser·p0.95:   7.668 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  26.386 ms/op
                 createUser·p0.9999: 30.540 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 5.561 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.668 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  29.227 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175280
  mean =      5.477 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 75064 
    [ 5.000,  7.500) = 88800 
    [ 7.500, 10.000) = 8940 
    [10.000, 12.500) = 1554 
    [12.500, 15.000) = 478 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.921 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     27.001 ms/op
     p(99.9900) =     32.830 ms/op
     p(99.9990) =     34.864 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.560 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.104 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.307 ±(99.9%) 0.021 ms/op
Iteration   1: 5.365 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.930 ms/op
                 existUser·p0.99:   10.588 ms/op
                 existUser·p0.999:  24.388 ms/op
                 existUser·p0.9999: 32.524 ms/op
                 existUser·p1.00:   33.194 ms/op

Iteration   2: 5.261 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.068 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.938 ms/op
                 existUser·p0.99:   10.746 ms/op
                 existUser·p0.999:  17.297 ms/op
                 existUser·p0.9999: 34.205 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   3: 5.352 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.868 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   7.086 ms/op
                 existUser·p0.95:   8.036 ms/op
                 existUser·p0.99:   10.863 ms/op
                 existUser·p0.999:  26.917 ms/op
                 existUser·p0.9999: 31.040 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180066
  mean =      5.326 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 93277 
    [ 5.000,  7.500) = 74365 
    [ 7.500, 10.000) = 9694 
    [10.000, 12.500) = 1892 
    [12.500, 15.000) = 503 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.898 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     32.964 ms/op
     p(99.9990) =     34.616 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.904 ±(99.9%) 0.333 ms/op
# Warmup Iteration   2: 6.855 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.709 ±(99.9%) 0.024 ms/op
Iteration   1: 5.391 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   7.684 ms/op
                 getUser·p0.99:   10.322 ms/op
                 getUser·p0.999:  27.145 ms/op
                 getUser·p0.9999: 30.147 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   2: 5.552 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.290 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.053 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   11.015 ms/op
                 getUser·p0.999:  26.523 ms/op
                 getUser·p0.9999: 31.719 ms/op
                 getUser·p1.00:   32.178 ms/op

Iteration   3: 5.400 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.716 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.700 ms/op
                 getUser·p0.99:   10.682 ms/op
                 getUser·p0.999:  28.467 ms/op
                 getUser·p0.9999: 34.215 ms/op
                 getUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176110
  mean =      5.447 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 76865 
    [ 5.000,  7.500) = 87664 
    [ 7.500, 10.000) = 9052 
    [10.000, 12.500) = 1747 
    [12.500, 15.000) = 376 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     10.631 ms/op
     p(99.9000) =     27.157 ms/op
     p(99.9900) =     33.580 ms/op
     p(99.9990) =     34.519 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 18.075 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 8.236 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.640 ±(99.9%) 0.027 ms/op
Iteration   1: 6.518 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   8.307 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   13.065 ms/op
                 listUser·p0.999:  30.175 ms/op
                 listUser·p0.9999: 33.620 ms/op
                 listUser·p1.00:   36.897 ms/op

Iteration   2: 6.289 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.878 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   12.141 ms/op
                 listUser·p0.999:  28.738 ms/op
                 listUser·p0.9999: 36.170 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   3: 6.357 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.256 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  23.413 ms/op
                 listUser·p0.9999: 27.474 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150169
  mean =      6.386 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 10031 
    [ 5.000,  7.500) = 118849 
    [ 7.500, 10.000) = 15695 
    [10.000, 12.500) = 4055 
    [12.500, 15.000) = 873 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      5.939 ms/op
     p(90.0000) =      8.086 ms/op
     p(95.0000) =      9.470 ms/op
     p(99.0000) =     12.517 ms/op
     p(99.9000) =     26.968 ms/op
     p(99.9900) =     33.618 ms/op
     p(99.9990) =     36.634 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.493 ± 1.308  ops/ms
ClientPb.existUser                       thrpt       3   5.939 ± 1.950  ops/ms
ClientPb.getUser                         thrpt       3   5.725 ± 3.049  ops/ms
ClientPb.listUser                        thrpt       3   4.972 ± 0.662  ops/ms
ClientPb.createUser                       avgt       3   5.534 ± 1.000   ms/op
ClientPb.existUser                        avgt       3   5.274 ± 1.538   ms/op
ClientPb.getUser                          avgt       3   5.295 ± 1.337   ms/op
ClientPb.listUser                         avgt       3   6.341 ± 0.914   ms/op
ClientPb.createUser                     sample  175280   5.477 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.647           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.921           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.897           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.699           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.001           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.830           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  180066   5.326 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.898           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.979           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.513           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.964           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  176110   5.447 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.262           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.631           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.157           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.580           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  150169   6.386 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.458           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.939           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.086           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.470           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.517           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.968           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.618           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.897           ms/op
