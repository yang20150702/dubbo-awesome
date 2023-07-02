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
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 8.445 ops/ms
Iteration   1: 8.804 ops/ms
Iteration   2: 9.103 ops/ms
Iteration   3: 9.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.988 ±(99.9%) 2.940 ops/ms [Average]
  (min, avg, max) = (8.804, 8.988, 9.103), stdev = 0.161
  CI (99.9%): [6.048, 11.928] (assumes normal distribution)


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
# Warmup Iteration   1: 3.178 ops/ms
# Warmup Iteration   2: 9.037 ops/ms
# Warmup Iteration   3: 9.381 ops/ms
Iteration   1: 9.534 ops/ms
Iteration   2: 9.670 ops/ms
Iteration   3: 9.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.590 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (9.534, 9.590, 9.670), stdev = 0.071
  CI (99.9%): [8.289, 10.892] (assumes normal distribution)


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
# Warmup Iteration   1: 3.276 ops/ms
# Warmup Iteration   2: 8.389 ops/ms
# Warmup Iteration   3: 9.112 ops/ms
Iteration   1: 9.390 ops/ms
Iteration   2: 9.206 ops/ms
Iteration   3: 9.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.330 ±(99.9%) 1.958 ops/ms [Average]
  (min, avg, max) = (9.206, 9.330, 9.395), stdev = 0.107
  CI (99.9%): [7.373, 11.288] (assumes normal distribution)


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
# Warmup Iteration   1: 2.949 ops/ms
# Warmup Iteration   2: 7.339 ops/ms
# Warmup Iteration   3: 7.728 ops/ms
Iteration   1: 8.090 ops/ms
Iteration   2: 7.644 ops/ms
Iteration   3: 7.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.831 ±(99.9%) 4.227 ops/ms [Average]
  (min, avg, max) = (7.644, 7.831, 8.090), stdev = 0.232
  CI (99.9%): [3.604, 12.057] (assumes normal distribution)


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
# Warmup Iteration   1: 11.008 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.304 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.004 ms/op
Iteration   1: 3.467 ±(99.9%) 0.012 ms/op
Iteration   2: 3.448 ±(99.9%) 0.009 ms/op
Iteration   3: 3.372 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.429 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.372, 3.429, 3.467), stdev = 0.051
  CI (99.9%): [2.507, 4.351] (assumes normal distribution)


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
# Warmup Iteration   1: 9.366 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.008 ms/op
Iteration   1: 3.344 ±(99.9%) 0.006 ms/op
Iteration   2: 3.246 ±(99.9%) 0.010 ms/op
Iteration   3: 3.199 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.263 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (3.199, 3.263, 3.344), stdev = 0.074
  CI (99.9%): [1.911, 4.615] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.753 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.003 ms/op
Iteration   1: 3.610 ±(99.9%) 0.003 ms/op
Iteration   2: 3.429 ±(99.9%) 0.005 ms/op
Iteration   3: 3.523 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.521 ±(99.9%) 1.650 ms/op [Average]
  (min, avg, max) = (3.429, 3.521, 3.610), stdev = 0.090
  CI (99.9%): [1.871, 5.170] (assumes normal distribution)


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
# Warmup Iteration   1: 11.590 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.008 ms/op
Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
Iteration   3: 4.041 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.028 ±(99.9%) 2.316 ms/op [Average]
  (min, avg, max) = (3.894, 4.028, 4.147), stdev = 0.127
  CI (99.9%): [1.712, 6.344] (assumes normal distribution)


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
# Warmup Iteration   1: 9.443 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.012 ms/op
Iteration   1: 3.389 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.629 ms/op
                 createUser·p0.999:  21.222 ms/op
                 createUser·p0.9999: 24.168 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.397 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  23.433 ms/op
                 createUser·p0.9999: 28.659 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   3: 3.563 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  18.426 ms/op
                 createUser·p0.9999: 29.885 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278249
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6991 
    [ 2.500,  5.000) = 265954 
    [ 5.000,  7.500) = 4288 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     18.637 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     30.397 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.375 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.009 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.077 ms/op
                 existUser·p0.999:  21.207 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   2: 3.380 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  22.264 ms/op
                 existUser·p0.9999: 30.441 ms/op
                 existUser·p1.00:   31.752 ms/op

Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  8.311 ms/op
                 existUser·p0.9999: 39.631 ms/op
                 existUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285889
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 279912 
    [ 5.000, 10.000) = 5642 
    [10.000, 15.000) = 79 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 182 
    [25.000, 30.000) = 25 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     10.799 ms/op
     p(99.9900) =     37.737 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.649 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.012 ms/op
Iteration   1: 3.486 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  20.919 ms/op
                 getUser·p0.9999: 26.301 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  24.478 ms/op
                 getUser·p0.9999: 28.036 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.541 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  20.461 ms/op
                 getUser·p0.9999: 46.334 ms/op
                 getUser·p1.00:   46.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274011
  mean =      3.500 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267685 
    [ 5.000, 10.000) = 5799 
    [10.000, 15.000) = 189 
    [15.000, 20.000) = 50 
    [20.000, 25.000) = 140 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     45.810 ms/op
     p(99.9990) =     46.662 ms/op
     p(99.9999) =     46.662 ms/op
    p(100.0000) =     46.662 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.225 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.315 ±(99.9%) 0.015 ms/op
Iteration   1: 4.122 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  22.724 ms/op
                 listUser·p0.9999: 28.073 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   2: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   8.005 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.071 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233829
  mean =      4.101 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 220230 
    [ 5.000,  7.500) = 10725 
    [ 7.500, 10.000) = 1918 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     18.126 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     28.989 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.988 ± 2.940  ops/ms
ClientPb.existUser                       thrpt       3   9.590 ± 1.301  ops/ms
ClientPb.getUser                         thrpt       3   9.330 ± 1.958  ops/ms
ClientPb.listUser                        thrpt       3   7.831 ± 4.227  ops/ms
ClientPb.createUser                       avgt       3   3.429 ± 0.922   ms/op
ClientPb.existUser                        avgt       3   3.263 ± 1.352   ms/op
ClientPb.getUser                          avgt       3   3.521 ± 1.650   ms/op
ClientPb.listUser                         avgt       3   4.028 ± 2.316   ms/op
ClientPb.createUser                     sample  278249   3.448 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.061           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.637           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.705           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.507           ms/op
ClientPb.existUser                      sample  285889   3.356 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.799           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.737           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.567           ms/op
ClientPb.getUser                        sample  274011   3.500 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.840           ms/op
ClientPb.getUser:getUser·p0.9999        sample          45.810           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.662           ms/op
ClientPb.listUser                       sample  233829   4.101 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.307           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.153           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.782           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.477           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.655           ms/op
