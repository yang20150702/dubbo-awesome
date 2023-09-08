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
# Warmup Iteration   1: 1.538 ops/ms
# Warmup Iteration   2: 3.580 ops/ms
# Warmup Iteration   3: 7.039 ops/ms
Iteration   1: 6.930 ops/ms
Iteration   2: 7.626 ops/ms
Iteration   3: 7.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.461 ±(99.9%) 8.586 ops/ms [Average]
  (min, avg, max) = (6.930, 7.461, 7.826), stdev = 0.471
  CI (99.9%): [≈ 0, 16.046] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.289 ops/ms
# Warmup Iteration   2: 6.197 ops/ms
# Warmup Iteration   3: 7.932 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.218 ±(99.9%) 2.170 ops/ms [Average]
  (min, avg, max) = (8.139, 8.218, 8.355), stdev = 0.119
  CI (99.9%): [6.048, 10.388] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.942 ops/ms
# Warmup Iteration   2: 6.238 ops/ms
# Warmup Iteration   3: 7.643 ops/ms
Iteration   1: 7.923 ops/ms
Iteration   2: 7.694 ops/ms
Iteration   3: 7.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.810 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (7.694, 7.810, 7.923), stdev = 0.115
  CI (99.9%): [5.717, 9.903] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.851 ops/ms
# Warmup Iteration   2: 5.547 ops/ms
# Warmup Iteration   3: 6.371 ops/ms
Iteration   1: 6.490 ops/ms
Iteration   2: 6.674 ops/ms
Iteration   3: 6.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.661 ±(99.9%) 2.998 ops/ms [Average]
  (min, avg, max) = (6.490, 6.661, 6.818), stdev = 0.164
  CI (99.9%): [3.663, 9.659] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.429 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.444 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.463 ±(99.9%) 0.004 ms/op
Iteration   1: 4.139 ±(99.9%) 0.008 ms/op
Iteration   2: 4.131 ±(99.9%) 0.007 ms/op
Iteration   3: 4.049 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.106 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (4.049, 4.106, 4.139), stdev = 0.049
  CI (99.9%): [3.204, 5.009] (assumes normal distribution)


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
# Warmup Iteration   1: 13.067 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.006 ms/op
Iteration   1: 3.973 ±(99.9%) 0.003 ms/op
Iteration   2: 4.062 ±(99.9%) 0.008 ms/op
Iteration   3: 3.958 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.998 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.958, 3.998, 4.062), stdev = 0.057
  CI (99.9%): [2.967, 5.029] (assumes normal distribution)


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
# Warmup Iteration   1: 12.718 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.839 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.004 ms/op
Iteration   1: 4.144 ±(99.9%) 0.006 ms/op
Iteration   2: 3.980 ±(99.9%) 0.005 ms/op
Iteration   3: 4.090 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.071 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (3.980, 4.071, 4.144), stdev = 0.084
  CI (99.9%): [2.540, 5.602] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.181 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.054 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.014 ms/op
Iteration   1: 4.847 ±(99.9%) 0.015 ms/op
Iteration   2: 4.778 ±(99.9%) 0.012 ms/op
Iteration   3: 4.899 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.841 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (4.778, 4.841, 4.899), stdev = 0.060
  CI (99.9%): [3.738, 5.945] (assumes normal distribution)


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
# Warmup Iteration   1: 12.487 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.309 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.684 ±(99.9%) 0.023 ms/op
Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   7.405 ms/op
                 createUser·p0.999:  23.816 ms/op
                 createUser·p0.9999: 27.338 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   2: 4.108 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   5.081 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  15.073 ms/op
                 createUser·p0.9999: 42.276 ms/op
                 createUser·p1.00:   42.729 ms/op

Iteration   3: 4.138 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.095 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  27.677 ms/op
                 createUser·p0.9999: 30.745 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234423
  mean =      4.094 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221410 
    [ 5.000, 10.000) = 12108 
    [10.000, 15.000) = 597 
    [15.000, 20.000) = 40 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 133 
    [30.000, 35.000) = 46 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     24.005 ms/op
     p(99.9900) =     40.603 ms/op
     p(99.9990) =     42.707 ms/op
     p(99.9999) =     42.729 ms/op
    p(100.0000) =     42.729 ms/op


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
# Warmup Iteration   1: 12.725 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.014 ms/op
Iteration   1: 4.105 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.970 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   8.552 ms/op
                 existUser·p0.999:  13.747 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 4.304 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.009 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 30.474 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   3: 4.074 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   9.191 ms/op
                 existUser·p0.999:  28.198 ms/op
                 existUser·p0.9999: 31.856 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 230747
  mean =      4.159 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 195 
    [ 2.500,  5.000) = 208953 
    [ 5.000,  7.500) = 16725 
    [ 7.500, 10.000) = 3686 
    [10.000, 12.500) = 743 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     30.974 ms/op
     p(99.9990) =     32.203 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 14.880 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.354 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.014 ms/op
Iteration   1: 4.232 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   9.308 ms/op
                 getUser·p0.999:  13.694 ms/op
                 getUser·p0.9999: 29.671 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   2: 4.313 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  20.709 ms/op
                 getUser·p0.9999: 30.171 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   3: 4.211 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   8.339 ms/op
                 getUser·p0.999:  12.500 ms/op
                 getUser·p0.9999: 29.668 ms/op
                 getUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 225825
  mean =      4.251 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 207378 
    [ 5.000,  7.500) = 13349 
    [ 7.500, 10.000) = 3838 
    [10.000, 12.500) = 862 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     17.806 ms/op
     p(99.9900) =     29.879 ms/op
     p(99.9990) =     30.677 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 15.556 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.808 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.016 ±(99.9%) 0.022 ms/op
Iteration   1: 4.912 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  26.542 ms/op
                 listUser·p0.9999: 30.343 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 4.918 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 27.214 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   3: 4.955 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.691 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   9.582 ms/op
                 listUser·p0.999:  20.250 ms/op
                 listUser·p0.9999: 23.694 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194595
  mean =      4.928 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 148583 
    [ 5.000,  7.500) = 39462 
    [ 7.500, 10.000) = 4873 
    [10.000, 12.500) = 991 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     28.380 ms/op
     p(99.9990) =     30.907 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.461 ± 8.586  ops/ms
ClientPb.existUser                       thrpt       3   8.218 ± 2.170  ops/ms
ClientPb.getUser                         thrpt       3   7.810 ± 2.093  ops/ms
ClientPb.listUser                        thrpt       3   6.661 ± 2.998  ops/ms
ClientPb.createUser                       avgt       3   4.106 ± 0.902   ms/op
ClientPb.existUser                        avgt       3   3.998 ± 1.031   ms/op
ClientPb.getUser                          avgt       3   4.071 ± 1.531   ms/op
ClientPb.listUser                         avgt       3   4.841 ± 1.104   ms/op
ClientPb.createUser                     sample  234423   4.094 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.748           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.005           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.603           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.729           ms/op
ClientPb.existUser                      sample  230747   4.159 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.704           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.700           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.728           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.974           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  225825   4.251 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.720           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.962           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.806           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.879           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.556           ms/op
ClientPb.listUser                       sample  194595   4.928 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.683           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.265           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.380           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.031           ms/op
