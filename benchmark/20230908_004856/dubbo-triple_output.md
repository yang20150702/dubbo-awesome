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
# Warmup Iteration   1: 2.498 ops/ms
# Warmup Iteration   2: 5.870 ops/ms
# Warmup Iteration   3: 8.696 ops/ms
Iteration   1: 9.892 ops/ms
Iteration   2: 9.546 ops/ms
Iteration   3: 9.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.779 ±(99.9%) 3.676 ops/ms [Average]
  (min, avg, max) = (9.546, 9.779, 9.898), stdev = 0.202
  CI (99.9%): [6.103, 13.455] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ops/ms
# Warmup Iteration   2: 9.306 ops/ms
# Warmup Iteration   3: 10.068 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 9.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.168 ±(99.9%) 7.843 ops/ms [Average]
  (min, avg, max) = (9.822, 10.168, 10.649), stdev = 0.430
  CI (99.9%): [2.326, 18.011] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 9.746 ops/ms
Iteration   1: 9.664 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 10.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.946 ±(99.9%) 4.607 ops/ms [Average]
  (min, avg, max) = (9.664, 9.946, 10.151), stdev = 0.253
  CI (99.9%): [5.339, 14.553] (assumes normal distribution)


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
# Warmup Iteration   1: 3.324 ops/ms
# Warmup Iteration   2: 7.696 ops/ms
# Warmup Iteration   3: 8.342 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.471 ops/ms
Iteration   3: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.407 ±(99.9%) 1.130 ops/ms [Average]
  (min, avg, max) = (8.348, 8.407, 8.471), stdev = 0.062
  CI (99.9%): [7.277, 9.537] (assumes normal distribution)


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
# Warmup Iteration   1: 8.351 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.003 ms/op
Iteration   1: 3.211 ±(99.9%) 0.002 ms/op
Iteration   2: 3.206 ±(99.9%) 0.004 ms/op
Iteration   3: 3.261 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.226 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.206, 3.226, 3.261), stdev = 0.031
  CI (99.9%): [2.667, 3.786] (assumes normal distribution)


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
# Warmup Iteration   1: 7.949 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.004 ms/op
Iteration   1: 3.216 ±(99.9%) 0.003 ms/op
Iteration   2: 3.091 ±(99.9%) 0.004 ms/op
Iteration   3: 3.164 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.157 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (3.091, 3.157, 3.216), stdev = 0.062
  CI (99.9%): [2.018, 4.296] (assumes normal distribution)


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
# Warmup Iteration   1: 7.439 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.002 ms/op
Iteration   1: 3.206 ±(99.9%) 0.004 ms/op
Iteration   2: 3.164 ±(99.9%) 0.004 ms/op
Iteration   3: 3.282 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.164, 3.218, 3.282), stdev = 0.060
  CI (99.9%): [2.128, 4.307] (assumes normal distribution)


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
# Warmup Iteration   1: 8.729 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.005 ms/op
Iteration   1: 3.786 ±(99.9%) 0.007 ms/op
Iteration   2: 3.750 ±(99.9%) 0.010 ms/op
Iteration   3: 3.829 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.788 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (3.750, 3.788, 3.829), stdev = 0.039
  CI (99.9%): [3.068, 4.508] (assumes normal distribution)


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
# Warmup Iteration   1: 8.296 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.011 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  11.886 ms/op
                 createUser·p0.9999: 22.343 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  20.898 ms/op
                 createUser·p0.9999: 23.730 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   3: 3.411 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.667 ms/op
                 createUser·p0.999:  15.171 ms/op
                 createUser·p0.9999: 20.100 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292724
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18119 
    [ 2.500,  5.000) = 267246 
    [ 5.000,  7.500) = 6088 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     16.389 ms/op
     p(99.9900) =     23.355 ms/op
     p(99.9990) =     23.996 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 7.658 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  10.565 ms/op
                 existUser·p0.9999: 20.224 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  14.303 ms/op
                 existUser·p0.9999: 22.639 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  15.458 ms/op
                 existUser·p0.9999: 21.186 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293660
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23529 
    [ 2.500,  5.000) = 262361 
    [ 5.000,  7.500) = 6167 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     23.007 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 8.163 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.012 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  20.204 ms/op
                 getUser·p0.9999: 24.650 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.510 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  12.927 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284774
  mean =      3.370 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8967 
    [ 2.500,  5.000) = 267609 
    [ 5.000,  7.500) = 6551 
    [ 7.500, 10.000) = 1270 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     12.914 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 11.073 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.014 ms/op
Iteration   1: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.698 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  15.967 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 3.803 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.628 ms/op
                 listUser·p0.999:  14.171 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.932 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 22.474 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247630
  mean =      3.876 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 239567 
    [ 5.000,  7.500) = 5480 
    [ 7.500, 10.000) = 1649 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     14.725 ms/op
     p(99.9900) =     20.914 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.779 ± 3.676  ops/ms
ClientPb.existUser                       thrpt       3  10.168 ± 7.843  ops/ms
ClientPb.getUser                         thrpt       3   9.946 ± 4.607  ops/ms
ClientPb.listUser                        thrpt       3   8.407 ± 1.130  ops/ms
ClientPb.createUser                       avgt       3   3.226 ± 0.559   ms/op
ClientPb.existUser                        avgt       3   3.157 ± 1.139   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 1.090   ms/op
ClientPb.listUser                         avgt       3   3.788 ± 0.720   ms/op
ClientPb.createUser                     sample  292724   3.281 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.090           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.389           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.355           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.936           ms/op
ClientPb.existUser                      sample  293660   3.266 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  284774   3.370 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.836           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.914           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.183           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.871           ms/op
ClientPb.listUser                       sample  247630   3.876 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.698           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.914           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.512           ms/op
