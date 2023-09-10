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
# Warmup Iteration   1: 1.225 ops/ms
# Warmup Iteration   2: 2.585 ops/ms
# Warmup Iteration   3: 5.645 ops/ms
Iteration   1: 5.832 ops/ms
Iteration   2: 6.325 ops/ms
Iteration   3: 6.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.152 ±(99.9%) 5.062 ops/ms [Average]
  (min, avg, max) = (5.832, 6.152, 6.325), stdev = 0.277
  CI (99.9%): [1.090, 11.214] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.667 ops/ms
# Warmup Iteration   2: 5.237 ops/ms
# Warmup Iteration   3: 6.239 ops/ms
Iteration   1: 6.229 ops/ms
Iteration   2: 6.523 ops/ms
Iteration   3: 6.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.414 ±(99.9%) 2.940 ops/ms [Average]
  (min, avg, max) = (6.229, 6.414, 6.523), stdev = 0.161
  CI (99.9%): [3.474, 9.353] (assumes normal distribution)


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
# Warmup Iteration   1: 1.677 ops/ms
# Warmup Iteration   2: 5.022 ops/ms
# Warmup Iteration   3: 5.879 ops/ms
Iteration   1: 5.952 ops/ms
Iteration   2: 6.032 ops/ms
Iteration   3: 6.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.007 ±(99.9%) 0.869 ops/ms [Average]
  (min, avg, max) = (5.952, 6.007, 6.036), stdev = 0.048
  CI (99.9%): [5.138, 6.875] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.733 ops/ms
# Warmup Iteration   2: 4.445 ops/ms
# Warmup Iteration   3: 5.086 ops/ms
Iteration   1: 5.157 ops/ms
Iteration   2: 5.234 ops/ms
Iteration   3: 5.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.256 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (5.157, 5.256, 5.378), stdev = 0.112
  CI (99.9%): [3.213, 7.300] (assumes normal distribution)


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
# Warmup Iteration   1: 16.863 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.493 ±(99.9%) 0.013 ms/op
Iteration   1: 5.350 ±(99.9%) 0.011 ms/op
Iteration   2: 5.248 ±(99.9%) 0.005 ms/op
Iteration   3: 5.151 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.250 ±(99.9%) 1.814 ms/op [Average]
  (min, avg, max) = (5.151, 5.250, 5.350), stdev = 0.099
  CI (99.9%): [3.436, 7.064] (assumes normal distribution)


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
# Warmup Iteration   1: 15.189 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.751 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.160 ±(99.9%) 0.009 ms/op
Iteration   1: 5.003 ±(99.9%) 0.005 ms/op
Iteration   2: 5.004 ±(99.9%) 0.009 ms/op
Iteration   3: 4.943 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.983 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (4.943, 4.983, 5.004), stdev = 0.035
  CI (99.9%): [4.346, 5.621] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.275 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.919 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.418 ±(99.9%) 0.010 ms/op
Iteration   1: 5.261 ±(99.9%) 0.009 ms/op
Iteration   2: 5.321 ±(99.9%) 0.012 ms/op
Iteration   3: 5.204 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.262 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (5.204, 5.262, 5.321), stdev = 0.059
  CI (99.9%): [4.192, 6.333] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.642 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.297 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.242 ±(99.9%) 0.014 ms/op
Iteration   1: 6.232 ±(99.9%) 0.010 ms/op
Iteration   2: 5.991 ±(99.9%) 0.019 ms/op
Iteration   3: 6.185 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.136 ±(99.9%) 2.331 ms/op [Average]
  (min, avg, max) = (5.991, 6.136, 6.232), stdev = 0.128
  CI (99.9%): [3.805, 8.466] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.754 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.905 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.663 ±(99.9%) 0.026 ms/op
Iteration   1: 5.414 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  24.740 ms/op
                 createUser·p0.9999: 31.693 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   2: 5.362 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.913 ms/op
                 createUser·p0.99:   10.580 ms/op
                 createUser·p0.999:  23.146 ms/op
                 createUser·p0.9999: 26.905 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 5.246 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.406 ms/op
                 createUser·p0.95:   7.315 ms/op
                 createUser·p0.99:   9.963 ms/op
                 createUser·p0.999:  25.299 ms/op
                 createUser·p0.9999: 30.397 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179697
  mean =      5.340 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 87416 
    [ 5.000,  7.500) = 82046 
    [ 7.500, 10.000) = 7900 
    [10.000, 12.500) = 1571 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     34.211 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 15.327 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.762 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.251 ±(99.9%) 0.019 ms/op
Iteration   1: 5.113 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.154 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.266 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  20.463 ms/op
                 existUser·p0.9999: 23.617 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 5.194 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.832 ms/op
                 existUser·p0.99:   10.732 ms/op
                 existUser·p0.999:  21.002 ms/op
                 existUser·p0.9999: 26.930 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 5.158 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  24.970 ms/op
                 existUser·p0.9999: 27.256 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186193
  mean =      5.155 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 110557 
    [ 5.000,  7.500) = 66510 
    [ 7.500, 10.000) = 7040 
    [10.000, 12.500) = 1322 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     22.034 ms/op
     p(99.9900) =     26.634 ms/op
     p(99.9990) =     27.898 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.750 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 5.764 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.253 ±(99.9%) 0.019 ms/op
Iteration   1: 5.375 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.425 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   8.060 ms/op
                 getUser·p0.99:   11.812 ms/op
                 getUser·p0.999:  22.921 ms/op
                 getUser·p0.9999: 28.878 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   2: 5.178 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.788 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   11.583 ms/op
                 getUser·p0.999:  26.548 ms/op
                 getUser·p0.9999: 29.962 ms/op
                 getUser·p1.00:   31.785 ms/op

Iteration   3: 5.104 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.490 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.201 ms/op
                 getUser·p0.95:   6.980 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  28.443 ms/op
                 getUser·p0.9999: 32.947 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184111
  mean =      5.216 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 103508 
    [ 5.000,  7.500) = 70584 
    [ 7.500, 10.000) = 7484 
    [10.000, 12.500) = 1480 
    [12.500, 15.000) = 548 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     31.771 ms/op
     p(99.9990) =     33.913 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 19.165 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 7.406 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.435 ±(99.9%) 0.027 ms/op
Iteration   1: 6.279 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.663 ms/op
                 listUser·p0.999:  28.443 ms/op
                 listUser·p0.9999: 33.158 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   2: 6.292 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   13.114 ms/op
                 listUser·p0.999:  28.054 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   31.719 ms/op

Iteration   3: 6.249 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.064 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   12.451 ms/op
                 listUser·p0.999:  25.021 ms/op
                 listUser·p0.9999: 28.735 ms/op
                 listUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153078
  mean =      6.274 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 9813 
    [ 5.000,  7.500) = 127027 
    [ 7.500, 10.000) = 12257 
    [10.000, 12.500) = 2524 
    [12.500, 15.000) = 759 
    [15.000, 17.500) = 267 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.576 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     12.324 ms/op
     p(99.9000) =     27.225 ms/op
     p(99.9900) =     32.463 ms/op
     p(99.9990) =     33.748 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.152 ± 5.062  ops/ms
ClientPb.existUser                       thrpt       3   6.414 ± 2.940  ops/ms
ClientPb.getUser                         thrpt       3   6.007 ± 0.869  ops/ms
ClientPb.listUser                        thrpt       3   5.256 ± 2.043  ops/ms
ClientPb.createUser                       avgt       3   5.250 ± 1.814   ms/op
ClientPb.existUser                        avgt       3   4.983 ± 0.637   ms/op
ClientPb.getUser                          avgt       3   5.262 ± 1.070   ms/op
ClientPb.listUser                         avgt       3   6.136 ± 2.331   ms/op
ClientPb.createUser                     sample  179697   5.340 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.204           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.636           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.437           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.150           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.933           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  186193   5.155 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.154           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.463           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.034           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.634           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  184111   5.216 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.788           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.643           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.846           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.150           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.771           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  153078   6.274 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.576           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.225           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.463           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.079           ms/op
