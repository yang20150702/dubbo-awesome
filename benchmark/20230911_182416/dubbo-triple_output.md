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
# Warmup Iteration   1: 1.266 ops/ms
# Warmup Iteration   2: 3.236 ops/ms
# Warmup Iteration   3: 6.055 ops/ms
Iteration   1: 6.309 ops/ms
Iteration   2: 6.605 ops/ms
Iteration   3: 6.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.519 ±(99.9%) 3.333 ops/ms [Average]
  (min, avg, max) = (6.309, 6.519, 6.643), stdev = 0.183
  CI (99.9%): [3.186, 9.852] (assumes normal distribution)


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
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 6.216 ops/ms
# Warmup Iteration   3: 6.885 ops/ms
Iteration   1: 6.934 ops/ms
Iteration   2: 6.869 ops/ms
Iteration   3: 7.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.953 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (6.869, 6.953, 7.056), stdev = 0.095
  CI (99.9%): [5.218, 8.689] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.150 ops/ms
# Warmup Iteration   2: 6.327 ops/ms
# Warmup Iteration   3: 6.578 ops/ms
Iteration   1: 6.451 ops/ms
Iteration   2: 6.581 ops/ms
Iteration   3: 6.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.550 ±(99.9%) 1.586 ops/ms [Average]
  (min, avg, max) = (6.451, 6.550, 6.616), stdev = 0.087
  CI (99.9%): [4.964, 8.135] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.908 ops/ms
# Warmup Iteration   2: 4.911 ops/ms
# Warmup Iteration   3: 5.599 ops/ms
Iteration   1: 5.677 ops/ms
Iteration   2: 5.850 ops/ms
Iteration   3: 5.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.738 ±(99.9%) 1.776 ops/ms [Average]
  (min, avg, max) = (5.677, 5.738, 5.850), stdev = 0.097
  CI (99.9%): [3.962, 7.513] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.219 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 6.741 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.230 ±(99.9%) 0.012 ms/op
Iteration   1: 5.238 ±(99.9%) 0.010 ms/op
Iteration   2: 4.927 ±(99.9%) 0.015 ms/op
Iteration   3: 5.067 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.078 ±(99.9%) 2.845 ms/op [Average]
  (min, avg, max) = (4.927, 5.078, 5.238), stdev = 0.156
  CI (99.9%): [2.232, 7.923] (assumes normal distribution)


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
# Warmup Iteration   1: 13.341 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.134 ±(99.9%) 0.007 ms/op
Iteration   1: 4.863 ±(99.9%) 0.009 ms/op
Iteration   2: 4.947 ±(99.9%) 0.006 ms/op
Iteration   3: 5.026 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.945 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (4.863, 4.945, 5.026), stdev = 0.082
  CI (99.9%): [3.458, 6.433] (assumes normal distribution)


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
# Warmup Iteration   1: 17.705 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.890 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.195 ±(99.9%) 0.010 ms/op
Iteration   1: 5.232 ±(99.9%) 0.012 ms/op
Iteration   2: 5.211 ±(99.9%) 0.008 ms/op
Iteration   3: 5.167 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.203 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (5.167, 5.203, 5.232), stdev = 0.033
  CI (99.9%): [4.604, 5.803] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.805 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 7.283 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.134 ±(99.9%) 0.011 ms/op
Iteration   1: 5.984 ±(99.9%) 0.014 ms/op
Iteration   2: 5.813 ±(99.9%) 0.017 ms/op
Iteration   3: 5.896 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.898 ±(99.9%) 1.557 ms/op [Average]
  (min, avg, max) = (5.813, 5.898, 5.984), stdev = 0.085
  CI (99.9%): [4.341, 7.454] (assumes normal distribution)


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
# Warmup Iteration   1: 15.521 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 6.086 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.216 ±(99.9%) 0.023 ms/op
Iteration   1: 5.215 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.167 ms/op
                 createUser·p0.50:   4.899 ms/op
                 createUser·p0.90:   6.480 ms/op
                 createUser·p0.95:   7.537 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  22.827 ms/op
                 createUser·p0.9999: 34.004 ms/op
                 createUser·p1.00:   35.062 ms/op

Iteration   2: 4.943 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   9.290 ms/op
                 createUser·p0.999:  21.642 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 4.970 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   4.702 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.849 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  26.350 ms/op
                 createUser·p0.9999: 33.475 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190510
  mean =      5.040 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 119837 
    [ 5.000,  7.500) = 63510 
    [ 7.500, 10.000) = 5319 
    [10.000, 12.500) = 1124 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 83 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     22.656 ms/op
     p(99.9900) =     33.194 ms/op
     p(99.9990) =     34.706 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.587 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.440 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.953 ±(99.9%) 0.018 ms/op
Iteration   1: 5.068 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.676 ms/op
                 existUser·p0.99:   10.666 ms/op
                 existUser·p0.999:  20.618 ms/op
                 existUser·p0.9999: 24.883 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   2: 5.150 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.105 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.528 ms/op
                 existUser·p0.99:   10.093 ms/op
                 existUser·p0.999:  24.674 ms/op
                 existUser·p0.9999: 30.107 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   3: 4.990 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  23.846 ms/op
                 existUser·p0.9999: 32.263 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189326
  mean =      5.068 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 117686 
    [ 5.000,  7.500) = 62120 
    [ 7.500, 10.000) = 7257 
    [10.000, 12.500) = 1475 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     21.700 ms/op
     p(99.9900) =     30.116 ms/op
     p(99.9990) =     32.494 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 15.474 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 5.497 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.020 ms/op
Iteration   1: 5.005 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.042 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   6.947 ms/op
                 getUser·p0.99:   10.184 ms/op
                 getUser·p0.999:  20.612 ms/op
                 getUser·p0.9999: 32.388 ms/op
                 getUser·p1.00:   33.292 ms/op

Iteration   2: 4.976 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.273 ms/op
                 getUser·p0.50:   4.760 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   6.865 ms/op
                 getUser·p0.99:   9.110 ms/op
                 getUser·p0.999:  20.215 ms/op
                 getUser·p0.9999: 30.110 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 4.924 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.914 ms/op
                 getUser·p0.99:   10.124 ms/op
                 getUser·p0.999:  19.159 ms/op
                 getUser·p0.9999: 27.936 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 193094
  mean =      4.968 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 125840 
    [ 5.000,  7.500) = 60469 
    [ 7.500, 10.000) = 5023 
    [10.000, 12.500) = 1106 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.042 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     18.544 ms/op
     p(99.9900) =     30.464 ms/op
     p(99.9990) =     33.262 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.640 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.659 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.394 ±(99.9%) 0.029 ms/op
Iteration   1: 6.057 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.359 ms/op
                 listUser·p0.999:  28.621 ms/op
                 listUser·p0.9999: 33.316 ms/op
                 listUser·p1.00:   35.193 ms/op

Iteration   2: 6.095 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  27.706 ms/op
                 listUser·p0.9999: 38.388 ms/op
                 listUser·p1.00:   40.763 ms/op

Iteration   3: 5.945 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  20.127 ms/op
                 listUser·p0.9999: 22.867 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159013
  mean =      6.032 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 18660 
    [ 5.000, 10.000) = 136692 
    [10.000, 15.000) = 3250 
    [15.000, 20.000) = 130 
    [20.000, 25.000) = 109 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      5.693 ms/op
     p(90.0000) =      7.266 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.614 ms/op
     p(99.9000) =     25.492 ms/op
     p(99.9900) =     36.307 ms/op
     p(99.9990) =     40.647 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.519 ± 3.333  ops/ms
ClientPb.existUser                       thrpt       3   6.953 ± 1.736  ops/ms
ClientPb.getUser                         thrpt       3   6.550 ± 1.586  ops/ms
ClientPb.listUser                        thrpt       3   5.738 ± 1.776  ops/ms
ClientPb.createUser                       avgt       3   5.078 ± 2.845   ms/op
ClientPb.existUser                        avgt       3   4.945 ± 1.487   ms/op
ClientPb.getUser                          avgt       3   5.203 ± 0.600   ms/op
ClientPb.listUser                         avgt       3   5.898 ± 1.557   ms/op
ClientPb.createUser                     sample  190510   5.040 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.847           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.656           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.194           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  189326   5.068 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.372           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.387           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.700           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.116           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  193094   4.968 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.042           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.798           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.544           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.464           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.292           ms/op
ClientPb.listUser                       sample  159013   6.032 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.614           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.492           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.307           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.763           ms/op
