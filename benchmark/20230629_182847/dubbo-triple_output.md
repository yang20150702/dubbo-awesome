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
# Warmup Iteration   1: 2.282 ops/ms
# Warmup Iteration   2: 5.693 ops/ms
# Warmup Iteration   3: 8.270 ops/ms
Iteration   1: 8.917 ops/ms
Iteration   2: 8.974 ops/ms
Iteration   3: 9.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.113 ±(99.9%) 5.313 ops/ms [Average]
  (min, avg, max) = (8.917, 9.113, 9.448), stdev = 0.291
  CI (99.9%): [3.800, 14.426] (assumes normal distribution)


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
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 9.136 ops/ms
# Warmup Iteration   3: 9.061 ops/ms
Iteration   1: 10.010 ops/ms
Iteration   2: 9.501 ops/ms
Iteration   3: 9.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.803 ±(99.9%) 4.877 ops/ms [Average]
  (min, avg, max) = (9.501, 9.803, 10.010), stdev = 0.267
  CI (99.9%): [4.926, 14.679] (assumes normal distribution)


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
# Warmup Iteration   1: 2.742 ops/ms
# Warmup Iteration   2: 8.036 ops/ms
# Warmup Iteration   3: 9.093 ops/ms
Iteration   1: 9.396 ops/ms
Iteration   2: 9.299 ops/ms
Iteration   3: 9.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.407 ±(99.9%) 2.069 ops/ms [Average]
  (min, avg, max) = (9.299, 9.407, 9.525), stdev = 0.113
  CI (99.9%): [7.338, 11.475] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.817 ops/ms
# Warmup Iteration   2: 7.414 ops/ms
# Warmup Iteration   3: 8.115 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.011 ±(99.9%) 3.440 ops/ms [Average]
  (min, avg, max) = (7.897, 8.011, 8.229), stdev = 0.189
  CI (99.9%): [4.571, 11.452] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.012 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.009 ms/op
Iteration   1: 3.430 ±(99.9%) 0.009 ms/op
Iteration   2: 3.593 ±(99.9%) 0.008 ms/op
Iteration   3: 3.468 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.497 ±(99.9%) 1.553 ms/op [Average]
  (min, avg, max) = (3.430, 3.497, 3.593), stdev = 0.085
  CI (99.9%): [1.944, 5.050] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.954 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.003 ms/op
Iteration   1: 3.253 ±(99.9%) 0.006 ms/op
Iteration   2: 3.266 ±(99.9%) 0.007 ms/op
Iteration   3: 3.219 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.246 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.219, 3.246, 3.266), stdev = 0.024
  CI (99.9%): [2.801, 3.691] (assumes normal distribution)


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
# Warmup Iteration   1: 9.597 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.004 ms/op
Iteration   1: 3.440 ±(99.9%) 0.004 ms/op
Iteration   2: 3.430 ±(99.9%) 0.006 ms/op
Iteration   3: 3.823 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.564 ±(99.9%) 4.093 ms/op [Average]
  (min, avg, max) = (3.430, 3.564, 3.823), stdev = 0.224
  CI (99.9%): [≈ 0, 7.657] (assumes normal distribution)


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
# Warmup Iteration   1: 11.027 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.008 ms/op
Iteration   1: 3.977 ±(99.9%) 0.011 ms/op
Iteration   2: 3.986 ±(99.9%) 0.009 ms/op
Iteration   3: 3.935 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.966 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.935, 3.966, 3.986), stdev = 0.027
  CI (99.9%): [3.466, 4.466] (assumes normal distribution)


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
# Warmup Iteration   1: 10.635 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.013 ms/op
Iteration   1: 3.576 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  20.285 ms/op
                 createUser·p0.9999: 25.039 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  22.364 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.406 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  18.986 ms/op
                 createUser·p0.9999: 27.682 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279345
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11053 
    [ 2.500,  5.000) = 262713 
    [ 5.000,  7.500) = 4202 
    [ 7.500, 10.000) = 756 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     19.289 ms/op
     p(99.9900) =     25.694 ms/op
     p(99.9990) =     28.691 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 8.290 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.009 ms/op
Iteration   1: 3.336 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  19.566 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.537 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.931 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.454 ms/op
                 existUser·p0.999:  22.891 ms/op
                 existUser·p0.9999: 29.489 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 3.352 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 26.669 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282253
  mean =      3.406 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8806 
    [ 2.500,  5.000) = 265493 
    [ 5.000,  7.500) = 7043 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 9.669 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.011 ms/op
Iteration   1: 3.422 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  16.193 ms/op
                 getUser·p0.9999: 24.158 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   2: 3.348 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.436 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  19.431 ms/op
                 getUser·p0.9999: 21.998 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  20.025 ms/op
                 getUser·p0.9999: 25.442 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281922
  mean =      3.403 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7792 
    [ 2.500,  5.000) = 267937 
    [ 5.000,  7.500) = 5115 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     24.766 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 12.213 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.834 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.013 ms/op
Iteration   1: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.992 ms/op
                 listUser·p0.999:  21.131 ms/op
                 listUser·p0.9999: 23.461 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.744 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 26.606 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   3: 3.996 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.855 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 15.531 ms/op
                 listUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240950
  mean =      3.985 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 232674 
    [ 5.000,  7.500) = 5749 
    [ 7.500, 10.000) = 1527 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     15.533 ms/op
     p(99.9900) =     24.212 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.113 ± 5.313  ops/ms
ClientPb.existUser                       thrpt       3   9.803 ± 4.877  ops/ms
ClientPb.getUser                         thrpt       3   9.407 ± 2.069  ops/ms
ClientPb.listUser                        thrpt       3   8.011 ± 3.440  ops/ms
ClientPb.createUser                       avgt       3   3.497 ± 1.553   ms/op
ClientPb.existUser                        avgt       3   3.246 ± 0.445   ms/op
ClientPb.getUser                          avgt       3   3.564 ± 4.093   ms/op
ClientPb.listUser                         avgt       3   3.966 ± 0.500   ms/op
ClientPb.createUser                     sample  279345   3.437 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.077           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.289           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.694           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.524           ms/op
ClientPb.existUser                      sample  282253   3.406 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.223           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.312           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.343           ms/op
ClientPb.getUser                        sample  281922   3.403 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.436           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.890           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.253           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.766           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  240950   3.985 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.533           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.212           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.673           ms/op
