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
# Warmup Iteration   1: 1.569 ops/ms
# Warmup Iteration   2: 3.537 ops/ms
# Warmup Iteration   3: 6.948 ops/ms
Iteration   1: 7.794 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 8.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.959 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (7.794, 7.959, 8.134), stdev = 0.170
  CI (99.9%): [4.857, 11.061] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.337 ops/ms
# Warmup Iteration   2: 6.545 ops/ms
# Warmup Iteration   3: 7.934 ops/ms
Iteration   1: 8.502 ops/ms
Iteration   2: 8.531 ops/ms
Iteration   3: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.331 ±(99.9%) 5.880 ops/ms [Average]
  (min, avg, max) = (7.959, 8.331, 8.531), stdev = 0.322
  CI (99.9%): [2.451, 14.211] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.173 ops/ms
# Warmup Iteration   2: 6.814 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 8.046 ops/ms
Iteration   2: 7.980 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.092 ±(99.9%) 2.576 ops/ms [Average]
  (min, avg, max) = (7.980, 8.092, 8.251), stdev = 0.141
  CI (99.9%): [5.516, 10.668] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 5.787 ops/ms
# Warmup Iteration   3: 6.821 ops/ms
Iteration   1: 7.043 ops/ms
Iteration   2: 7.145 ops/ms
Iteration   3: 6.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.051 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (6.964, 7.051, 7.145), stdev = 0.090
  CI (99.9%): [5.403, 8.699] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.581 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.007 ms/op
Iteration   1: 3.955 ±(99.9%) 0.007 ms/op
Iteration   2: 3.938 ±(99.9%) 0.013 ms/op
Iteration   3: 3.998 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.964 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.938, 3.964, 3.998), stdev = 0.030
  CI (99.9%): [3.408, 4.520] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.309 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.014 ms/op
Iteration   1: 3.785 ±(99.9%) 0.004 ms/op
Iteration   2: 3.892 ±(99.9%) 0.002 ms/op
Iteration   3: 3.717 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.798 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (3.717, 3.798, 3.892), stdev = 0.088
  CI (99.9%): [2.186, 5.410] (assumes normal distribution)


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
# Warmup Iteration   1: 12.092 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.006 ms/op
Iteration   1: 4.196 ±(99.9%) 0.012 ms/op
Iteration   2: 3.894 ±(99.9%) 0.010 ms/op
Iteration   3: 3.895 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.995 ±(99.9%) 3.172 ms/op [Average]
  (min, avg, max) = (3.894, 3.995, 4.196), stdev = 0.174
  CI (99.9%): [0.823, 7.167] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.796 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.401 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.008 ms/op
Iteration   1: 4.629 ±(99.9%) 0.014 ms/op
Iteration   2: 4.616 ±(99.9%) 0.010 ms/op
Iteration   3: 4.625 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.623 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (4.616, 4.623, 4.629), stdev = 0.007
  CI (99.9%): [4.500, 4.746] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.220 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.941 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.019 ms/op
Iteration   1: 3.997 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  11.942 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   2: 3.938 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  26.008 ms/op
                 createUser·p0.9999: 28.733 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 4.018 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  27.676 ms/op
                 createUser·p0.9999: 33.161 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241070
  mean =      3.984 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 229092 
    [ 5.000,  7.500) = 9889 
    [ 7.500, 10.000) = 1369 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     31.969 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 11.670 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
Iteration   1: 3.865 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  23.665 ms/op
                 existUser·p0.9999: 30.507 ms/op
                 existUser·p1.00:   31.523 ms/op

Iteration   2: 3.754 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  8.351 ms/op
                 existUser·p0.9999: 33.323 ms/op
                 existUser·p1.00:   33.751 ms/op

Iteration   3: 3.868 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.892 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  26.784 ms/op
                 existUser·p0.9999: 30.907 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250665
  mean =      3.828 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 274 
    [ 2.500,  5.000) = 242289 
    [ 5.000,  7.500) = 6637 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     32.635 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 12.483 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.015 ms/op
Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   8.028 ms/op
                 getUser·p0.999:  11.257 ms/op
                 getUser·p0.9999: 25.925 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 4.022 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   8.372 ms/op
                 getUser·p0.999:  26.182 ms/op
                 getUser·p0.9999: 38.435 ms/op
                 getUser·p1.00:   41.681 ms/op

Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  11.059 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238660
  mean =      4.022 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 225209 
    [ 5.000, 10.000) = 12841 
    [10.000, 15.000) = 354 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 62 
    [25.000, 30.000) = 128 
    [30.000, 35.000) = 52 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     40.622 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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
# Warmup Iteration   1: 14.293 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.423 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.902 ±(99.9%) 0.018 ms/op
Iteration   1: 4.735 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  24.327 ms/op
                 listUser·p0.9999: 27.451 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   2: 4.695 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  17.691 ms/op
                 listUser·p0.9999: 22.069 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.707 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 21.503 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203638
  mean =      4.712 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 173645 
    [ 5.000,  7.500) = 25606 
    [ 7.500, 10.000) = 3477 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      8.361 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     28.007 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.959 ± 3.102  ops/ms
ClientPb.existUser                       thrpt       3   8.331 ± 5.880  ops/ms
ClientPb.getUser                         thrpt       3   8.092 ± 2.576  ops/ms
ClientPb.listUser                        thrpt       3   7.051 ± 1.648  ops/ms
ClientPb.createUser                       avgt       3   3.964 ± 0.556   ms/op
ClientPb.existUser                        avgt       3   3.798 ± 1.612   ms/op
ClientPb.getUser                          avgt       3   3.995 ± 3.172   ms/op
ClientPb.listUser                         avgt       3   4.623 ± 0.123   ms/op
ClientPb.createUser                     sample  241070   3.984 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.047           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.168           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.691           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.969           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  250665   3.828 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.709           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.643           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.635           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  238660   4.022 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.376           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.987           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.429           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.751           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.681           ms/op
ClientPb.listUser                       sample  203638   4.712 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.264           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.361           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.235           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.739           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.180           ms/op
