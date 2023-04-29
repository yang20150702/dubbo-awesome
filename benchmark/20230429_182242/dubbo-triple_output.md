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
# Warmup Iteration   1: 1.664 ops/ms
# Warmup Iteration   2: 3.562 ops/ms
# Warmup Iteration   3: 7.240 ops/ms
Iteration   1: 7.530 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 7.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.793 ±(99.9%) 4.491 ops/ms [Average]
  (min, avg, max) = (7.530, 7.793, 8.019), stdev = 0.246
  CI (99.9%): [3.302, 12.284] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.238 ops/ms
# Warmup Iteration   2: 7.302 ops/ms
# Warmup Iteration   3: 7.890 ops/ms
Iteration   1: 8.261 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.384 ±(99.9%) 2.275 ops/ms [Average]
  (min, avg, max) = (8.261, 8.384, 8.510), stdev = 0.125
  CI (99.9%): [6.109, 10.659] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.319 ops/ms
# Warmup Iteration   2: 7.068 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.896 ±(99.9%) 3.917 ops/ms [Average]
  (min, avg, max) = (7.763, 7.896, 8.143), stdev = 0.215
  CI (99.9%): [3.978, 11.813] (assumes normal distribution)


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
# Warmup Iteration   1: 2.162 ops/ms
# Warmup Iteration   2: 5.630 ops/ms
# Warmup Iteration   3: 6.622 ops/ms
Iteration   1: 6.450 ops/ms
Iteration   2: 6.912 ops/ms
Iteration   3: 6.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.738 ±(99.9%) 4.579 ops/ms [Average]
  (min, avg, max) = (6.450, 6.738, 6.912), stdev = 0.251
  CI (99.9%): [2.158, 11.317] (assumes normal distribution)


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
# Warmup Iteration   1: 13.268 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.011 ms/op
Iteration   1: 4.030 ±(99.9%) 0.009 ms/op
Iteration   2: 3.903 ±(99.9%) 0.010 ms/op
Iteration   3: 3.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.972 ±(99.9%) 1.172 ms/op [Average]
  (min, avg, max) = (3.903, 3.972, 4.030), stdev = 0.064
  CI (99.9%): [2.800, 5.145] (assumes normal distribution)


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
# Warmup Iteration   1: 11.492 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.746 ±(99.9%) 0.005 ms/op
Iteration   2: 3.840 ±(99.9%) 0.005 ms/op
Iteration   3: 3.811 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.799 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.746, 3.799, 3.840), stdev = 0.048
  CI (99.9%): [2.919, 4.679] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.273 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.714 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.007 ms/op
Iteration   1: 4.094 ±(99.9%) 0.008 ms/op
Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
Iteration   3: 4.000 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.040 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (4.000, 4.040, 4.094), stdev = 0.049
  CI (99.9%): [3.153, 4.927] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.672 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.479 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.016 ms/op
Iteration   1: 4.523 ±(99.9%) 0.014 ms/op
Iteration   2: 4.745 ±(99.9%) 0.007 ms/op
Iteration   3: 4.544 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.604 ±(99.9%) 2.238 ms/op [Average]
  (min, avg, max) = (4.523, 4.604, 4.745), stdev = 0.123
  CI (99.9%): [2.366, 6.842] (assumes normal distribution)


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
# Warmup Iteration   1: 11.543 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.017 ms/op
Iteration   1: 4.096 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  13.057 ms/op
                 createUser·p0.9999: 26.495 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  25.715 ms/op
                 createUser·p0.9999: 33.618 ms/op
                 createUser·p1.00:   33.882 ms/op

Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.071 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  11.549 ms/op
                 createUser·p0.9999: 32.414 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236407
  mean =      4.059 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 221605 
    [ 5.000,  7.500) = 12329 
    [ 7.500, 10.000) = 1557 
    [10.000, 12.500) = 385 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     13.127 ms/op
     p(99.9900) =     32.419 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 11.278 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.013 ms/op
Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.224 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 28.403 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 4.088 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.847 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  25.619 ms/op
                 existUser·p0.9999: 30.098 ms/op
                 existUser·p1.00:   30.900 ms/op

Iteration   3: 3.948 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.928 ms/op
                 existUser·p0.999:  13.575 ms/op
                 existUser·p0.9999: 32.863 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241426
  mean =      3.975 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 276 
    [ 2.500,  5.000) = 226813 
    [ 5.000,  7.500) = 12195 
    [ 7.500, 10.000) = 1434 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     33.500 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 13.638 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.924 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
Iteration   1: 4.221 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   6.758 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  23.887 ms/op
                 getUser·p0.9999: 32.416 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   2: 4.187 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.401 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  15.466 ms/op
                 getUser·p0.9999: 38.535 ms/op
                 getUser·p1.00:   40.960 ms/op

Iteration   3: 3.881 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  26.821 ms/op
                 getUser·p0.9999: 30.433 ms/op
                 getUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234628
  mean =      4.091 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 217093 
    [ 5.000, 10.000) = 16415 
    [10.000, 15.000) = 844 
    [15.000, 20.000) = 12 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 139 
    [30.000, 35.000) = 46 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     37.224 ms/op
     p(99.9990) =     40.350 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


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
# Warmup Iteration   1: 14.191 ±(99.9%) 0.216 ms/op
# Warmup Iteration   2: 5.406 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.849 ±(99.9%) 0.017 ms/op
Iteration   1: 4.728 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   8.862 ms/op
                 listUser·p0.999:  25.854 ms/op
                 listUser·p0.9999: 30.613 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   2: 4.553 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.366 ms/op
                 listUser·p0.999:  17.820 ms/op
                 listUser·p0.9999: 24.706 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   3: 4.499 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 18.392 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208838
  mean =      4.591 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 182729 
    [ 5.000,  7.500) = 21892 
    [ 7.500, 10.000) = 3113 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     17.995 ms/op
     p(99.9900) =     28.994 ms/op
     p(99.9990) =     31.474 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.793 ± 4.491  ops/ms
ClientPb.existUser                       thrpt       3   8.384 ± 2.275  ops/ms
ClientPb.getUser                         thrpt       3   7.896 ± 3.917  ops/ms
ClientPb.listUser                        thrpt       3   6.738 ± 4.579  ops/ms
ClientPb.createUser                       avgt       3   3.972 ± 1.172   ms/op
ClientPb.existUser                        avgt       3   3.799 ± 0.880   ms/op
ClientPb.getUser                          avgt       3   4.040 ± 0.887   ms/op
ClientPb.listUser                         avgt       3   4.604 ± 2.238   ms/op
ClientPb.createUser                     sample  236407   4.059 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.406           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.127           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.419           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  241426   3.975 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.214           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.746           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.097           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  234628   4.091 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.409           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.986           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.224           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.960           ms/op
ClientPb.listUser                       sample  208838   4.591 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.343           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.995           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.801           ms/op
