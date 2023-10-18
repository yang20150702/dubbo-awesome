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
# Warmup Iteration   1: 1.169 ops/ms
# Warmup Iteration   2: 2.535 ops/ms
# Warmup Iteration   3: 5.549 ops/ms
Iteration   1: 5.685 ops/ms
Iteration   2: 5.952 ops/ms
Iteration   3: 6.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.886 ±(99.9%) 3.223 ops/ms [Average]
  (min, avg, max) = (5.685, 5.886, 6.019), stdev = 0.177
  CI (99.9%): [2.663, 9.108] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 5.209 ops/ms
# Warmup Iteration   3: 6.107 ops/ms
Iteration   1: 6.331 ops/ms
Iteration   2: 6.316 ops/ms
Iteration   3: 6.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.287 ±(99.9%) 1.162 ops/ms [Average]
  (min, avg, max) = (6.214, 6.287, 6.331), stdev = 0.064
  CI (99.9%): [5.125, 7.449] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.779 ops/ms
# Warmup Iteration   2: 5.045 ops/ms
# Warmup Iteration   3: 5.899 ops/ms
Iteration   1: 5.723 ops/ms
Iteration   2: 5.815 ops/ms
Iteration   3: 5.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.744 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (5.694, 5.744, 5.815), stdev = 0.063
  CI (99.9%): [4.591, 6.897] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.593 ops/ms
# Warmup Iteration   2: 4.137 ops/ms
# Warmup Iteration   3: 4.908 ops/ms
Iteration   1: 5.115 ops/ms
Iteration   2: 5.103 ops/ms
Iteration   3: 5.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.167 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (5.103, 5.167, 5.284), stdev = 0.101
  CI (99.9%): [3.325, 7.009] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 17.242 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.407 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.897 ±(99.9%) 0.010 ms/op
Iteration   1: 5.459 ±(99.9%) 0.012 ms/op
Iteration   2: 5.413 ±(99.9%) 0.009 ms/op
Iteration   3: 5.542 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.471 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (5.413, 5.471, 5.542), stdev = 0.066
  CI (99.9%): [4.275, 6.668] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 16.598 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.766 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.007 ms/op
Iteration   1: 5.278 ±(99.9%) 0.006 ms/op
Iteration   2: 5.118 ±(99.9%) 0.017 ms/op
Iteration   3: 5.138 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.178 ±(99.9%) 1.599 ms/op [Average]
  (min, avg, max) = (5.118, 5.178, 5.278), stdev = 0.088
  CI (99.9%): [3.579, 6.777] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 16.689 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.480 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.507 ±(99.9%) 0.009 ms/op
Iteration   1: 5.517 ±(99.9%) 0.007 ms/op
Iteration   2: 5.257 ±(99.9%) 0.010 ms/op
Iteration   3: 5.433 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.403 ±(99.9%) 2.419 ms/op [Average]
  (min, avg, max) = (5.257, 5.403, 5.517), stdev = 0.133
  CI (99.9%): [2.983, 7.822] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.481 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 8.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.404 ±(99.9%) 0.016 ms/op
Iteration   1: 6.273 ±(99.9%) 0.008 ms/op
Iteration   2: 6.314 ±(99.9%) 0.013 ms/op
Iteration   3: 6.301 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.296 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (6.273, 6.296, 6.314), stdev = 0.021
  CI (99.9%): [5.916, 6.676] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 17.737 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.952 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.055 ±(99.9%) 0.029 ms/op
Iteration   1: 5.532 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.355 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   10.009 ms/op
                 createUser·p0.999:  24.707 ms/op
                 createUser·p0.9999: 30.245 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   2: 5.740 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.487 ms/op
                 createUser·p0.99:   11.796 ms/op
                 createUser·p0.999:  26.879 ms/op
                 createUser·p0.9999: 30.156 ms/op
                 createUser·p1.00:   33.292 ms/op

Iteration   3: 5.556 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  28.391 ms/op
                 createUser·p0.9999: 31.662 ms/op
                 createUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171109
  mean =      5.608 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 59155 
    [ 5.000,  7.500) = 99410 
    [ 7.500, 10.000) = 10096 
    [10.000, 12.500) = 1558 
    [12.500, 15.000) = 435 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.273 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     26.706 ms/op
     p(99.9900) =     31.388 ms/op
     p(99.9990) =     33.269 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 15.532 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.443 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.243 ±(99.9%) 0.017 ms/op
Iteration   1: 5.380 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.710 ms/op
                 existUser·p0.95:   8.053 ms/op
                 existUser·p0.99:   11.956 ms/op
                 existUser·p0.999:  21.089 ms/op
                 existUser·p0.9999: 25.753 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 5.254 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.118 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.430 ms/op
                 existUser·p0.99:   10.158 ms/op
                 existUser·p0.999:  26.739 ms/op
                 existUser·p0.9999: 40.227 ms/op
                 existUser·p1.00:   42.140 ms/op

Iteration   3: 5.188 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.496 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  26.484 ms/op
                 existUser·p0.9999: 30.993 ms/op
                 existUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182060
  mean =      5.273 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 98076 
    [ 5.000, 10.000) = 81810 
    [10.000, 15.000) = 1753 
    [15.000, 20.000) = 191 
    [20.000, 25.000) = 88 
    [25.000, 30.000) = 94 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.427 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     35.966 ms/op
     p(99.9990) =     41.172 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.388 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.239 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.508 ±(99.9%) 0.019 ms/op
Iteration   1: 5.637 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.982 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   6.889 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   12.452 ms/op
                 getUser·p0.999:  25.526 ms/op
                 getUser·p0.9999: 29.076 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   2: 5.604 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.626 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   6.996 ms/op
                 getUser·p0.95:   8.266 ms/op
                 getUser·p0.99:   11.786 ms/op
                 getUser·p0.999:  27.191 ms/op
                 getUser·p0.9999: 30.546 ms/op
                 getUser·p1.00:   37.356 ms/op

Iteration   3: 5.427 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.900 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.438 ms/op
                 getUser·p0.99:   10.371 ms/op
                 getUser·p0.999:  25.493 ms/op
                 getUser·p0.9999: 28.847 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172787
  mean =      5.554 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 61048 
    [ 5.000,  7.500) = 100429 
    [ 7.500, 10.000) = 8134 
    [10.000, 12.500) = 1892 
    [12.500, 15.000) = 650 
    [15.000, 17.500) = 319 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.982 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     25.894 ms/op
     p(99.9900) =     29.974 ms/op
     p(99.9990) =     33.492 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 20.585 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.661 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.614 ±(99.9%) 0.025 ms/op
Iteration   1: 6.585 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.798 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   13.800 ms/op
                 listUser·p0.999:  24.782 ms/op
                 listUser·p0.9999: 26.776 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 6.667 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.687 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   13.981 ms/op
                 listUser·p0.999:  28.609 ms/op
                 listUser·p0.9999: 32.912 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 6.403 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.178 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.349 ms/op
                 listUser·p0.999:  23.038 ms/op
                 listUser·p0.9999: 29.623 ms/op
                 listUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146468
  mean =      6.550 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4675 
    [ 5.000,  7.500) = 122587 
    [ 7.500, 10.000) = 14552 
    [10.000, 12.500) = 2920 
    [12.500, 15.000) = 905 
    [15.000, 17.500) = 429 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.687 ms/op
     p(50.0000) =      6.185 ms/op
     p(90.0000) =      7.889 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     13.058 ms/op
     p(99.9000) =     24.969 ms/op
     p(99.9900) =     32.190 ms/op
     p(99.9990) =     33.478 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.886 ± 3.223  ops/ms
ClientPb.existUser                       thrpt       3   6.287 ± 1.162  ops/ms
ClientPb.getUser                         thrpt       3   5.744 ± 1.153  ops/ms
ClientPb.listUser                        thrpt       3   5.167 ± 1.842  ops/ms
ClientPb.createUser                       avgt       3   5.471 ± 1.196   ms/op
ClientPb.existUser                        avgt       3   5.178 ± 1.599   ms/op
ClientPb.getUser                          avgt       3   5.403 ± 2.419   ms/op
ClientPb.listUser                         avgt       3   6.296 ± 0.380   ms/op
ClientPb.createUser                     sample  171109   5.608 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.273           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.086           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.650           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.706           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.388           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  182060   5.273 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.118           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.595           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.627           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.427           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.266           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.966           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.140           ms/op
ClientPb.getUser                        sample  172787   5.554 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.982           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.020           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.534           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.894           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.974           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.356           ms/op
ClientPb.listUser                       sample  146468   6.550 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.687           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.058           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.969           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.190           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.554           ms/op
