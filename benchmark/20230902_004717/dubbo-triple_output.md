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
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 5.917 ops/ms
# Warmup Iteration   3: 8.945 ops/ms
Iteration   1: 9.170 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 9.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.309 ±(99.9%) 3.685 ops/ms [Average]
  (min, avg, max) = (9.170, 9.309, 9.540), stdev = 0.202
  CI (99.9%): [5.624, 12.994] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.688 ops/ms
# Warmup Iteration   2: 7.844 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.483 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.433 ±(99.9%) 1.454 ops/ms [Average]
  (min, avg, max) = (9.341, 9.433, 9.483), stdev = 0.080
  CI (99.9%): [7.979, 10.886] (assumes normal distribution)


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
# Warmup Iteration   1: 2.991 ops/ms
# Warmup Iteration   2: 8.440 ops/ms
# Warmup Iteration   3: 9.094 ops/ms
Iteration   1: 8.966 ops/ms
Iteration   2: 9.072 ops/ms
Iteration   3: 8.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.946 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (8.801, 8.946, 9.072), stdev = 0.136
  CI (99.9%): [6.458, 11.434] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 7.009 ops/ms
# Warmup Iteration   3: 7.800 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.004 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (7.922, 8.004, 8.114), stdev = 0.099
  CI (99.9%): [6.204, 9.805] (assumes normal distribution)


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
# Warmup Iteration   1: 9.059 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.007 ms/op
Iteration   1: 3.490 ±(99.9%) 0.004 ms/op
Iteration   2: 3.483 ±(99.9%) 0.012 ms/op
Iteration   3: 3.470 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.481 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (3.470, 3.481, 3.490), stdev = 0.010
  CI (99.9%): [3.299, 3.664] (assumes normal distribution)


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
# Warmup Iteration   1: 7.842 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.003 ms/op
Iteration   1: 3.315 ±(99.9%) 0.002 ms/op
Iteration   2: 3.318 ±(99.9%) 0.008 ms/op
Iteration   3: 3.200 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.278 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.200, 3.278, 3.318), stdev = 0.068
  CI (99.9%): [2.042, 4.514] (assumes normal distribution)


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
# Warmup Iteration   1: 8.841 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.004 ms/op
Iteration   1: 3.548 ±(99.9%) 0.008 ms/op
Iteration   2: 3.497 ±(99.9%) 0.007 ms/op
Iteration   3: 3.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.523 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.497, 3.523, 3.548), stdev = 0.025
  CI (99.9%): [3.064, 3.982] (assumes normal distribution)


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
# Warmup Iteration   1: 9.518 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.998 ±(99.9%) 0.010 ms/op
Iteration   2: 4.063 ±(99.9%) 0.009 ms/op
Iteration   3: 4.079 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.047 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.998, 4.047, 4.079), stdev = 0.043
  CI (99.9%): [3.271, 4.823] (assumes normal distribution)


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
# Warmup Iteration   1: 9.787 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.009 ms/op
Iteration   1: 3.539 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  19.796 ms/op
                 createUser·p0.9999: 22.740 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   2: 3.444 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.851 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  22.544 ms/op
                 createUser·p0.9999: 26.261 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.476 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.649 ms/op
                 createUser·p0.999:  24.408 ms/op
                 createUser·p0.9999: 27.623 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275429
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6925 
    [ 2.500,  5.000) = 259400 
    [ 5.000,  7.500) = 7401 
    [ 7.500, 10.000) = 1141 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 106 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     21.337 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     27.967 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.154 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
Iteration   1: 3.346 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   2: 3.282 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  15.776 ms/op
                 existUser·p0.9999: 31.597 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   3: 3.385 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  23.337 ms/op
                 existUser·p0.9999: 31.687 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287556
  mean =      3.337 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6450 
    [ 2.500,  5.000) = 273676 
    [ 5.000,  7.500) = 6092 
    [ 7.500, 10.000) = 927 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     11.682 ms/op
     p(99.9900) =     31.498 ms/op
     p(99.9990) =     31.986 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 9.590 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.012 ms/op
Iteration   1: 3.501 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 21.749 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  22.595 ms/op
                 getUser·p0.9999: 25.723 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   3: 3.438 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  18.478 ms/op
                 getUser·p0.9999: 35.852 ms/op
                 getUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277522
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 268187 
    [ 5.000, 10.000) = 8776 
    [10.000, 15.000) = 213 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 187 
    [25.000, 30.000) = 45 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     18.772 ms/op
     p(99.9900) =     33.964 ms/op
     p(99.9990) =     39.810 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


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
# Warmup Iteration   1: 10.424 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.014 ms/op
Iteration   1: 4.187 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 20.819 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 4.060 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 23.396 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.138 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  14.805 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232701
  mean =      4.128 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 220818 
    [ 5.000,  7.500) = 8458 
    [ 7.500, 10.000) = 2264 
    [10.000, 12.500) = 571 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      8.347 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     23.506 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.309 ± 3.685  ops/ms
ClientPb.existUser                       thrpt       3   9.433 ± 1.454  ops/ms
ClientPb.getUser                         thrpt       3   8.946 ± 2.488  ops/ms
ClientPb.listUser                        thrpt       3   8.004 ± 1.801  ops/ms
ClientPb.createUser                       avgt       3   3.481 ± 0.183   ms/op
ClientPb.existUser                        avgt       3   3.278 ± 1.236   ms/op
ClientPb.getUser                          avgt       3   3.523 ± 0.459   ms/op
ClientPb.listUser                         avgt       3   4.047 ± 0.776   ms/op
ClientPb.createUser                     sample  275429   3.486 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.214           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.337           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.837           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  287556   3.337 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.997           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.682           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.498           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  277522   3.458 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.772           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.964           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.108           ms/op
ClientPb.listUser                       sample  232701   4.128 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.102           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.347           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.184           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.593           ms/op
