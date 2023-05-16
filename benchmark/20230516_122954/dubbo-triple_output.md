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
# Warmup Iteration   1: 1.128 ops/ms
# Warmup Iteration   2: 2.344 ops/ms
# Warmup Iteration   3: 5.325 ops/ms
Iteration   1: 5.653 ops/ms
Iteration   2: 5.896 ops/ms
Iteration   3: 6.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.891 ±(99.9%) 4.286 ops/ms [Average]
  (min, avg, max) = (5.653, 5.891, 6.123), stdev = 0.235
  CI (99.9%): [1.605, 10.177] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.731 ops/ms
# Warmup Iteration   2: 5.865 ops/ms
# Warmup Iteration   3: 6.393 ops/ms
Iteration   1: 6.694 ops/ms
Iteration   2: 6.536 ops/ms
Iteration   3: 6.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.622 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (6.536, 6.622, 6.694), stdev = 0.080
  CI (99.9%): [5.163, 8.080] (assumes normal distribution)


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
# Warmup Iteration   1: 1.749 ops/ms
# Warmup Iteration   2: 5.212 ops/ms
# Warmup Iteration   3: 6.243 ops/ms
Iteration   1: 5.918 ops/ms
Iteration   2: 5.812 ops/ms
Iteration   3: 6.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.969 ±(99.9%) 3.420 ops/ms [Average]
  (min, avg, max) = (5.812, 5.969, 6.177), stdev = 0.187
  CI (99.9%): [2.549, 9.389] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.559 ops/ms
# Warmup Iteration   2: 4.451 ops/ms
# Warmup Iteration   3: 5.331 ops/ms
Iteration   1: 5.135 ops/ms
Iteration   2: 5.154 ops/ms
Iteration   3: 5.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.270 ±(99.9%) 3.976 ops/ms [Average]
  (min, avg, max) = (5.135, 5.270, 5.521), stdev = 0.218
  CI (99.9%): [1.295, 9.246] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.882 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.217 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.288 ±(99.9%) 0.015 ms/op
Iteration   1: 5.278 ±(99.9%) 0.015 ms/op
Iteration   2: 5.149 ±(99.9%) 0.016 ms/op
Iteration   3: 5.085 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.171 ±(99.9%) 1.801 ms/op [Average]
  (min, avg, max) = (5.085, 5.171, 5.278), stdev = 0.099
  CI (99.9%): [3.369, 6.972] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.249 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.933 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.181 ±(99.9%) 0.014 ms/op
Iteration   1: 5.338 ±(99.9%) 0.013 ms/op
Iteration   2: 5.232 ±(99.9%) 0.010 ms/op
Iteration   3: 5.224 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.265 ±(99.9%) 1.161 ms/op [Average]
  (min, avg, max) = (5.224, 5.265, 5.338), stdev = 0.064
  CI (99.9%): [4.104, 6.426] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.755 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.825 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.253 ±(99.9%) 0.012 ms/op
Iteration   1: 5.468 ±(99.9%) 0.009 ms/op
Iteration   2: 5.287 ±(99.9%) 0.015 ms/op
Iteration   3: 5.252 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.336 ±(99.9%) 2.119 ms/op [Average]
  (min, avg, max) = (5.252, 5.336, 5.468), stdev = 0.116
  CI (99.9%): [3.217, 7.455] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.305 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.015 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.996 ±(99.9%) 0.011 ms/op
Iteration   1: 6.091 ±(99.9%) 0.015 ms/op
Iteration   2: 5.971 ±(99.9%) 0.021 ms/op
Iteration   3: 5.946 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.003 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (5.946, 6.003, 6.091), stdev = 0.078
  CI (99.9%): [4.588, 7.418] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.157 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.813 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.849 ±(99.9%) 0.024 ms/op
Iteration   1: 5.383 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.400 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.513 ms/op
                 createUser·p0.95:   7.856 ms/op
                 createUser·p0.99:   10.305 ms/op
                 createUser·p0.999:  24.189 ms/op
                 createUser·p0.9999: 26.652 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   2: 5.441 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.274 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  25.370 ms/op
                 createUser·p0.9999: 34.013 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   3: 5.660 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.122 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  25.461 ms/op
                 createUser·p0.9999: 31.698 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174687
  mean =      5.492 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 63525 
    [ 5.000,  7.500) = 101772 
    [ 7.500, 10.000) = 7219 
    [10.000, 12.500) = 1389 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     24.914 ms/op
     p(99.9900) =     33.345 ms/op
     p(99.9990) =     34.375 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.906 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.015 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.358 ±(99.9%) 0.021 ms/op
Iteration   1: 5.132 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.232 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.332 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.355 ms/op
                 existUser·p0.999:  21.256 ms/op
                 existUser·p0.9999: 26.716 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   2: 5.180 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.380 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   7.348 ms/op
                 existUser·p0.99:   10.895 ms/op
                 existUser·p0.999:  24.911 ms/op
                 existUser·p0.9999: 28.928 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 4.986 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   9.684 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 27.668 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188209
  mean =      5.098 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 121312 
    [ 5.000,  7.500) = 58649 
    [ 7.500, 10.000) = 6041 
    [10.000, 12.500) = 1376 
    [12.500, 15.000) = 441 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      7.234 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     20.539 ms/op
     p(99.9900) =     28.055 ms/op
     p(99.9990) =     29.669 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.200 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.404 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.327 ±(99.9%) 0.019 ms/op
Iteration   1: 5.439 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.886 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.726 ms/op
                 getUser·p0.99:   10.761 ms/op
                 getUser·p0.999:  21.502 ms/op
                 getUser·p0.9999: 25.550 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   2: 5.573 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.955 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   12.173 ms/op
                 getUser·p0.999:  28.869 ms/op
                 getUser·p0.9999: 43.926 ms/op
                 getUser·p1.00:   44.696 ms/op

Iteration   3: 5.503 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.676 ms/op
                 getUser·p0.95:   7.479 ms/op
                 getUser·p0.99:   10.011 ms/op
                 getUser·p0.999:  15.134 ms/op
                 getUser·p0.9999: 28.154 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174322
  mean =      5.504 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 69258 
    [ 5.000, 10.000) = 102086 
    [10.000, 15.000) = 2584 
    [15.000, 20.000) = 196 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 95 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     22.108 ms/op
     p(99.9900) =     38.215 ms/op
     p(99.9990) =     44.696 ms/op
     p(99.9999) =     44.696 ms/op
    p(100.0000) =     44.696 ms/op


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
# Warmup Iteration   1: 20.065 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.575 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.192 ±(99.9%) 0.024 ms/op
Iteration   1: 6.230 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   11.796 ms/op
                 listUser·p0.999:  27.448 ms/op
                 listUser·p0.9999: 36.635 ms/op
                 listUser·p1.00:   38.011 ms/op

Iteration   2: 6.279 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  27.525 ms/op
                 listUser·p0.9999: 29.911 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   3: 6.256 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   15.090 ms/op
                 listUser·p0.999:  30.045 ms/op
                 listUser·p0.9999: 35.433 ms/op
                 listUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153418
  mean =      6.255 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 9737 
    [ 5.000,  7.500) = 127444 
    [ 7.500, 10.000) = 11930 
    [10.000, 12.500) = 2633 
    [12.500, 15.000) = 781 
    [15.000, 17.500) = 261 
    [17.500, 20.000) = 180 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      5.857 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.962 ms/op
     p(99.0000) =     12.812 ms/op
     p(99.9000) =     28.068 ms/op
     p(99.9900) =     35.564 ms/op
     p(99.9990) =     37.346 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.891 ± 4.286  ops/ms
ClientPb.existUser                       thrpt       3   6.622 ± 1.458  ops/ms
ClientPb.getUser                         thrpt       3   5.969 ± 3.420  ops/ms
ClientPb.listUser                        thrpt       3   5.270 ± 3.976  ops/ms
ClientPb.createUser                       avgt       3   5.171 ± 1.801   ms/op
ClientPb.existUser                        avgt       3   5.265 ± 1.161   ms/op
ClientPb.getUser                          avgt       3   5.336 ± 2.119   ms/op
ClientPb.listUser                         avgt       3   6.003 ± 1.415   ms/op
ClientPb.createUser                     sample  174687   5.492 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.122           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.660           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.387           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.914           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.345           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  188209   5.098 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.232           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.234           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.355           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.539           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.055           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  174322   5.504 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.182           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.840           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.174           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.108           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.215           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.696           ms/op
ClientPb.listUser                       sample  153418   6.255 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.964           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.962           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.812           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.068           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.564           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.011           ms/op
