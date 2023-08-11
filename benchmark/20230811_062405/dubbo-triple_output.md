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
# Warmup Iteration   1: 2.040 ops/ms
# Warmup Iteration   2: 4.783 ops/ms
# Warmup Iteration   3: 8.463 ops/ms
Iteration   1: 9.017 ops/ms
Iteration   2: 9.038 ops/ms
Iteration   3: 9.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.048 ±(99.9%) 0.659 ops/ms [Average]
  (min, avg, max) = (9.017, 9.048, 9.088), stdev = 0.036
  CI (99.9%): [8.389, 9.707] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 8.072 ops/ms
# Warmup Iteration   3: 8.856 ops/ms
Iteration   1: 9.387 ops/ms
Iteration   2: 9.650 ops/ms
Iteration   3: 9.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.605 ±(99.9%) 3.640 ops/ms [Average]
  (min, avg, max) = (9.387, 9.605, 9.779), stdev = 0.200
  CI (99.9%): [5.965, 13.245] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.634 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 9.047 ops/ms
Iteration   1: 9.028 ops/ms
Iteration   2: 9.208 ops/ms
Iteration   3: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.113 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (9.028, 9.113, 9.208), stdev = 0.091
  CI (99.9%): [7.461, 10.765] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 6.992 ops/ms
# Warmup Iteration   3: 7.314 ops/ms
Iteration   1: 7.630 ops/ms
Iteration   2: 7.606 ops/ms
Iteration   3: 7.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.708 ±(99.9%) 2.866 ops/ms [Average]
  (min, avg, max) = (7.606, 7.708, 7.889), stdev = 0.157
  CI (99.9%): [4.843, 10.574] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.072 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.004 ms/op
Iteration   1: 3.674 ±(99.9%) 0.006 ms/op
Iteration   2: 3.650 ±(99.9%) 0.005 ms/op
Iteration   3: 3.619 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.647 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.619, 3.647, 3.674), stdev = 0.028
  CI (99.9%): [3.142, 4.153] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.056 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.005 ms/op
Iteration   1: 3.427 ±(99.9%) 0.005 ms/op
Iteration   2: 3.314 ±(99.9%) 0.007 ms/op
Iteration   3: 3.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.427 ±(99.9%) 2.055 ms/op [Average]
  (min, avg, max) = (3.314, 3.427, 3.539), stdev = 0.113
  CI (99.9%): [1.372, 5.482] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 12.031 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.008 ms/op
Iteration   1: 3.525 ±(99.9%) 0.005 ms/op
Iteration   2: 3.578 ±(99.9%) 0.003 ms/op
Iteration   3: 3.438 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.514 ±(99.9%) 1.291 ms/op [Average]
  (min, avg, max) = (3.438, 3.514, 3.578), stdev = 0.071
  CI (99.9%): [2.223, 4.804] (assumes normal distribution)


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
# Warmup Iteration   1: 11.405 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.012 ms/op
Iteration   1: 4.119 ±(99.9%) 0.005 ms/op
Iteration   2: 4.059 ±(99.9%) 0.008 ms/op
Iteration   3: 4.031 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.070 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (4.031, 4.070, 4.119), stdev = 0.045
  CI (99.9%): [3.253, 4.886] (assumes normal distribution)


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
# Warmup Iteration   1: 10.746 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.017 ms/op
Iteration   1: 3.531 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  21.201 ms/op
                 createUser·p0.9999: 27.124 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 3.546 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  25.089 ms/op
                 createUser·p0.9999: 31.587 ms/op
                 createUser·p1.00:   32.997 ms/op

Iteration   3: 3.543 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  23.878 ms/op
                 createUser·p0.9999: 30.244 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271077
  mean =      3.540 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4407 
    [ 2.500,  5.000) = 259267 
    [ 5.000,  7.500) = 5693 
    [ 7.500, 10.000) = 980 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.482 ms/op
     p(99.9000) =     21.657 ms/op
     p(99.9900) =     30.729 ms/op
     p(99.9990) =     32.581 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.764 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
Iteration   1: 3.384 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  19.466 ms/op
                 existUser·p0.9999: 23.978 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.470 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.409 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  21.129 ms/op
                 existUser·p0.9999: 26.043 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 3.504 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 27.668 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277932
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11073 
    [ 2.500,  5.000) = 257439 
    [ 5.000,  7.500) = 7380 
    [ 7.500, 10.000) = 1402 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     26.314 ms/op
     p(99.9990) =     28.155 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 10.087 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.009 ms/op
Iteration   1: 3.533 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  22.315 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   2: 3.592 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  24.863 ms/op
                 getUser·p0.9999: 30.707 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   3: 3.573 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.735 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  20.153 ms/op
                 getUser·p0.9999: 30.769 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269047
  mean =      3.566 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5251 
    [ 2.500,  5.000) = 251577 
    [ 5.000,  7.500) = 10238 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     30.549 ms/op
     p(99.9990) =     31.596 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 12.705 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.016 ms/op
Iteration   1: 4.116 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  22.224 ms/op
                 listUser·p0.9999: 24.671 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 4.121 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  15.885 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234788
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 225650 
    [ 5.000,  7.500) = 6140 
    [ 7.500, 10.000) = 1884 
    [10.000, 12.500) = 578 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.751 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     24.691 ms/op
     p(99.9990) =     26.146 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.048 ± 0.659  ops/ms
ClientPb.existUser                       thrpt       3   9.605 ± 3.640  ops/ms
ClientPb.getUser                         thrpt       3   9.113 ± 1.652  ops/ms
ClientPb.listUser                        thrpt       3   7.708 ± 2.866  ops/ms
ClientPb.createUser                       avgt       3   3.647 ± 0.506   ms/op
ClientPb.existUser                        avgt       3   3.427 ± 2.055   ms/op
ClientPb.getUser                          avgt       3   3.514 ± 1.291   ms/op
ClientPb.listUser                         avgt       3   4.070 ± 0.817   ms/op
ClientPb.createUser                     sample  271077   3.540 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.372           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.482           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.657           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.729           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  277932   3.452 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.698           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.168           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.005           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.314           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  269047   3.566 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.976           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.881           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.955           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.549           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.850           ms/op
ClientPb.listUser                       sample  234788   4.087 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.751           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.691           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
