# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.023 ops/ms
# Warmup Iteration   2: 2.500 ops/ms
# Warmup Iteration   3: 5.058 ops/ms
Iteration   1: 5.506 ops/ms
Iteration   2: 5.702 ops/ms
Iteration   3: 5.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.687 ±(99.9%) 3.157 ops/ms [Average]
  (min, avg, max) = (5.506, 5.687, 5.852), stdev = 0.173
  CI (99.9%): [2.529, 8.844] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.585 ops/ms
# Warmup Iteration   2: 4.397 ops/ms
# Warmup Iteration   3: 5.593 ops/ms
Iteration   1: 5.951 ops/ms
Iteration   2: 5.875 ops/ms
Iteration   3: 5.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.892 ±(99.9%) 0.955 ops/ms [Average]
  (min, avg, max) = (5.851, 5.892, 5.951), stdev = 0.052
  CI (99.9%): [4.937, 6.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.488 ops/ms
# Warmup Iteration   2: 4.023 ops/ms
# Warmup Iteration   3: 5.517 ops/ms
Iteration   1: 5.576 ops/ms
Iteration   2: 5.631 ops/ms
Iteration   3: 5.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.686 ±(99.9%) 2.652 ops/ms [Average]
  (min, avg, max) = (5.576, 5.686, 5.851), stdev = 0.145
  CI (99.9%): [3.034, 8.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 3.872 ops/ms
# Warmup Iteration   3: 5.075 ops/ms
Iteration   1: 4.843 ops/ms
Iteration   2: 4.885 ops/ms
Iteration   3: 4.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.835 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (4.777, 4.835, 4.885), stdev = 0.055
  CI (99.9%): [3.841, 5.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.225 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.489 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.844 ±(99.9%) 0.009 ms/op
Iteration   1: 6.088 ±(99.9%) 0.007 ms/op
Iteration   2: 5.760 ±(99.9%) 0.012 ms/op
Iteration   3: 5.434 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.761 ±(99.9%) 5.969 ms/op [Average]
  (min, avg, max) = (5.434, 5.761, 6.088), stdev = 0.327
  CI (99.9%): [≈ 0, 11.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.286 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.989 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.429 ±(99.9%) 0.007 ms/op
Iteration   1: 5.325 ±(99.9%) 0.016 ms/op
Iteration   2: 5.269 ±(99.9%) 0.004 ms/op
Iteration   3: 5.567 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.387 ±(99.9%) 2.891 ms/op [Average]
  (min, avg, max) = (5.269, 5.387, 5.567), stdev = 0.158
  CI (99.9%): [2.496, 8.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.702 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.865 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.732 ±(99.9%) 0.011 ms/op
Iteration   1: 5.686 ±(99.9%) 0.007 ms/op
Iteration   2: 5.443 ±(99.9%) 0.015 ms/op
Iteration   3: 5.531 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.553 ±(99.9%) 2.243 ms/op [Average]
  (min, avg, max) = (5.443, 5.553, 5.686), stdev = 0.123
  CI (99.9%): [3.310, 7.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.817 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.912 ±(99.9%) 0.010 ms/op
Iteration   1: 6.744 ±(99.9%) 0.008 ms/op
Iteration   2: 6.382 ±(99.9%) 0.018 ms/op
Iteration   3: 6.426 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.517 ±(99.9%) 3.604 ms/op [Average]
  (min, avg, max) = (6.382, 6.517, 6.744), stdev = 0.198
  CI (99.9%): [2.913, 10.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.274 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 8.093 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.406 ±(99.9%) 0.027 ms/op
Iteration   1: 6.094 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   5.775 ms/op
                 createUser·p0.90:   7.725 ms/op
                 createUser·p0.95:   8.897 ms/op
                 createUser·p0.99:   12.081 ms/op
                 createUser·p0.999:  24.248 ms/op
                 createUser·p0.9999: 29.827 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   2: 6.012 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.400 ms/op
                 createUser·p0.50:   5.775 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.364 ms/op
                 createUser·p0.99:   11.141 ms/op
                 createUser·p0.999:  19.523 ms/op
                 createUser·p0.9999: 27.689 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 5.871 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.437 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.356 ms/op
                 createUser·p0.95:   8.274 ms/op
                 createUser·p0.99:   10.398 ms/op
                 createUser·p0.999:  27.187 ms/op
                 createUser·p0.9999: 30.547 ms/op
                 createUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 160117
  mean =      5.991 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 32210 
    [ 5.000,  7.500) = 112158 
    [ 7.500, 10.000) = 12531 
    [10.000, 12.500) = 2353 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      5.710 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     24.179 ms/op
     p(99.9900) =     29.852 ms/op
     p(99.9990) =     31.510 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.061 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 6.427 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.561 ±(99.9%) 0.022 ms/op
Iteration   1: 5.375 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.560 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.791 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  17.614 ms/op
                 existUser·p0.9999: 29.398 ms/op
                 existUser·p1.00:   31.031 ms/op

Iteration   2: 5.244 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.507 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.488 ms/op
                 existUser·p0.95:   7.455 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  24.019 ms/op
                 existUser·p0.9999: 27.213 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 5.230 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.414 ms/op
                 existUser·p0.95:   7.430 ms/op
                 existUser·p0.99:   11.043 ms/op
                 existUser·p0.999:  27.026 ms/op
                 existUser·p0.9999: 30.147 ms/op
                 existUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181493
  mean =      5.282 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 93473 
    [ 5.000,  7.500) = 78399 
    [ 7.500, 10.000) = 7642 
    [10.000, 12.500) = 1223 
    [12.500, 15.000) = 418 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =     10.175 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     29.612 ms/op
     p(99.9990) =     30.711 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.745 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.709 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.042 ±(99.9%) 0.025 ms/op
Iteration   1: 5.652 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.195 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.020 ms/op
                 getUser·p0.99:   9.929 ms/op
                 getUser·p0.999:  14.982 ms/op
                 getUser·p0.9999: 27.449 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 6.000 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.461 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   7.733 ms/op
                 getUser·p0.95:   9.008 ms/op
                 getUser·p0.99:   13.274 ms/op
                 getUser·p0.999:  29.184 ms/op
                 getUser·p0.9999: 36.459 ms/op
                 getUser·p1.00:   36.569 ms/op

Iteration   3: 5.780 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.654 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   6.939 ms/op
                 getUser·p0.95:   7.979 ms/op
                 getUser·p0.99:   10.386 ms/op
                 getUser·p0.999:  27.056 ms/op
                 getUser·p0.9999: 30.439 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165264
  mean =      5.807 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 37710 
    [ 5.000,  7.500) = 113563 
    [ 7.500, 10.000) = 11095 
    [10.000, 12.500) = 1901 
    [12.500, 15.000) = 535 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     26.632 ms/op
     p(99.9900) =     33.275 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.279 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 7.611 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.719 ±(99.9%) 0.027 ms/op
Iteration   1: 6.589 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.113 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   11.446 ms/op
                 listUser·p0.999:  28.651 ms/op
                 listUser·p0.9999: 30.970 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 6.628 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  34.537 ms/op
                 listUser·p0.9999: 45.744 ms/op
                 listUser·p1.00:   47.251 ms/op

Iteration   3: 6.701 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.323 ms/op
                 listUser·p0.95:   9.961 ms/op
                 listUser·p0.99:   14.041 ms/op
                 listUser·p0.999:  26.365 ms/op
                 listUser·p0.9999: 36.650 ms/op
                 listUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144589
  mean =      6.639 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4451 
    [ 5.000, 10.000) = 134856 
    [10.000, 15.000) = 4619 
    [15.000, 20.000) = 381 
    [20.000, 25.000) = 29 
    [25.000, 30.000) = 105 
    [30.000, 35.000) = 85 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      6.283 ms/op
     p(90.0000) =      8.086 ms/op
     p(95.0000) =      9.322 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     30.173 ms/op
     p(99.9900) =     45.029 ms/op
     p(99.9990) =     47.222 ms/op
     p(99.9999) =     47.251 ms/op
    p(100.0000) =     47.251 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.687 ± 3.157  ops/ms
ClientPb.existUser                       thrpt       3   5.892 ± 0.955  ops/ms
ClientPb.getUser                         thrpt       3   5.686 ± 2.652  ops/ms
ClientPb.listUser                        thrpt       3   4.835 ± 0.995  ops/ms
ClientPb.createUser                       avgt       3   5.761 ± 5.969   ms/op
ClientPb.existUser                        avgt       3   5.387 ± 2.891   ms/op
ClientPb.getUser                          avgt       3   5.553 ± 2.243   ms/op
ClientPb.listUser                         avgt       3   6.517 ± 3.604   ms/op
ClientPb.createUser                     sample  160117   5.991 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.556           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.479           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.487           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.207           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.179           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.852           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588           ms/op
ClientPb.existUser                      sample  181493   5.282 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.134           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.570           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.578           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.175           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.906           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.612           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.031           ms/op
ClientPb.getUser                        sample  165264   5.807 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.461           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.489           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.242           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.315           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.305           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.632           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.275           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.569           ms/op
ClientPb.listUser                       sample  144589   6.639 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.283           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.086           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.322           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.173           ms/op
ClientPb.listUser:listUser·p0.9999      sample          45.029           ms/op
ClientPb.listUser:listUser·p1.00        sample          47.251           ms/op
