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
# Warmup Iteration   1: 1.572 ops/ms
# Warmup Iteration   2: 3.600 ops/ms
# Warmup Iteration   3: 7.394 ops/ms
Iteration   1: 7.368 ops/ms
Iteration   2: 8.227 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.864 ±(99.9%) 8.109 ops/ms [Average]
  (min, avg, max) = (7.368, 7.864, 8.227), stdev = 0.444
  CI (99.9%): [≈ 0, 15.973] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 6.970 ops/ms
# Warmup Iteration   3: 7.831 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 8.568 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.221 ±(99.9%) 5.875 ops/ms [Average]
  (min, avg, max) = (7.931, 8.221, 8.568), stdev = 0.322
  CI (99.9%): [2.346, 14.096] (assumes normal distribution)


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
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 6.712 ops/ms
# Warmup Iteration   3: 7.534 ops/ms
Iteration   1: 8.085 ops/ms
Iteration   2: 7.983 ops/ms
Iteration   3: 7.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.949 ±(99.9%) 2.857 ops/ms [Average]
  (min, avg, max) = (7.778, 7.949, 8.085), stdev = 0.157
  CI (99.9%): [5.091, 10.806] (assumes normal distribution)


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
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 5.639 ops/ms
# Warmup Iteration   3: 6.504 ops/ms
Iteration   1: 6.809 ops/ms
Iteration   2: 6.723 ops/ms
Iteration   3: 6.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.821 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (6.723, 6.821, 6.931), stdev = 0.104
  CI (99.9%): [4.916, 8.727] (assumes normal distribution)


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
# Warmup Iteration   1: 13.618 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.006 ms/op
Iteration   1: 4.140 ±(99.9%) 0.007 ms/op
Iteration   2: 4.018 ±(99.9%) 0.005 ms/op
Iteration   3: 4.003 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.054 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (4.003, 4.054, 4.140), stdev = 0.075
  CI (99.9%): [2.688, 5.419] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.182 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.006 ms/op
Iteration   1: 3.686 ±(99.9%) 0.009 ms/op
Iteration   2: 4.092 ±(99.9%) 0.006 ms/op
Iteration   3: 3.927 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.902 ±(99.9%) 3.732 ms/op [Average]
  (min, avg, max) = (3.686, 3.902, 4.092), stdev = 0.205
  CI (99.9%): [0.170, 7.633] (assumes normal distribution)


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
# Warmup Iteration   1: 12.559 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.005 ms/op
Iteration   1: 3.944 ±(99.9%) 0.009 ms/op
Iteration   2: 3.910 ±(99.9%) 0.005 ms/op
Iteration   3: 4.046 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.967 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (3.910, 3.967, 4.046), stdev = 0.071
  CI (99.9%): [2.675, 5.259] (assumes normal distribution)


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
# Warmup Iteration   1: 14.225 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.388 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.763 ±(99.9%) 0.013 ms/op
Iteration   1: 4.798 ±(99.9%) 0.006 ms/op
Iteration   2: 4.882 ±(99.9%) 0.013 ms/op
Iteration   3: 4.734 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.805 ±(99.9%) 1.349 ms/op [Average]
  (min, avg, max) = (4.734, 4.805, 4.882), stdev = 0.074
  CI (99.9%): [3.455, 6.154] (assumes normal distribution)


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
# Warmup Iteration   1: 14.494 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.397 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.018 ms/op
Iteration   1: 3.960 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.214 ms/op
                 createUser·p0.999:  22.194 ms/op
                 createUser·p0.9999: 29.350 ms/op
                 createUser·p1.00:   32.670 ms/op

Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  12.760 ms/op
                 createUser·p0.9999: 26.768 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 4.185 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  27.728 ms/op
                 createUser·p0.9999: 31.406 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238322
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 481 
    [ 2.500,  5.000) = 223103 
    [ 5.000,  7.500) = 12522 
    [ 7.500, 10.000) = 1556 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     22.675 ms/op
     p(99.9900) =     30.485 ms/op
     p(99.9990) =     32.532 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 11.012 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
Iteration   1: 4.171 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   6.349 ms/op
                 existUser·p0.99:   8.102 ms/op
                 existUser·p0.999:  23.768 ms/op
                 existUser·p0.9999: 27.722 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  14.860 ms/op
                 existUser·p0.9999: 26.932 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 3.670 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 34.079 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244856
  mean =      3.919 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 370 
    [ 2.500,  5.000) = 229094 
    [ 5.000,  7.500) = 12894 
    [ 7.500, 10.000) = 1832 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     34.820 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 12.605 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
Iteration   1: 4.013 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.735 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   8.033 ms/op
                 getUser·p0.999:  14.631 ms/op
                 getUser·p0.9999: 27.002 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 4.121 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   8.208 ms/op
                 getUser·p0.999:  15.144 ms/op
                 getUser·p0.9999: 26.910 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.962 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.729 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.539 ms/op
                 getUser·p0.999:  27.359 ms/op
                 getUser·p0.9999: 40.820 ms/op
                 getUser·p1.00:   41.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237978
  mean =      4.031 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221934 
    [ 5.000, 10.000) = 15294 
    [10.000, 15.000) = 503 
    [15.000, 20.000) = 23 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 153 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.729 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     15.238 ms/op
     p(99.9900) =     39.518 ms/op
     p(99.9990) =     41.263 ms/op
     p(99.9999) =     41.353 ms/op
    p(100.0000) =     41.353 ms/op


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
# Warmup Iteration   1: 12.709 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.841 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.020 ms/op
Iteration   1: 4.701 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  24.478 ms/op
                 listUser·p0.9999: 31.241 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   2: 4.659 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 21.419 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.627 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  16.298 ms/op
                 listUser·p0.9999: 18.719 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205783
  mean =      4.662 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 180404 
    [ 5.000,  7.500) = 20378 
    [ 7.500, 10.000) = 3791 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     18.502 ms/op
     p(99.9900) =     28.643 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.864 ± 8.109  ops/ms
ClientPb.existUser                       thrpt       3   8.221 ± 5.875  ops/ms
ClientPb.getUser                         thrpt       3   7.949 ± 2.857  ops/ms
ClientPb.listUser                        thrpt       3   6.821 ± 1.906  ops/ms
ClientPb.createUser                       avgt       3   4.054 ± 1.365   ms/op
ClientPb.existUser                        avgt       3   3.902 ± 3.732   ms/op
ClientPb.getUser                          avgt       3   3.967 ± 1.292   ms/op
ClientPb.listUser                         avgt       3   4.805 ± 1.349   ms/op
ClientPb.createUser                     sample  238322   4.026 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.333           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.675           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.485           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.899           ms/op
ClientPb.existUser                      sample  244856   3.919 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.147           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.520           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.860           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.260           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  237978   4.031 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.729           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.238           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.518           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.353           ms/op
ClientPb.listUser                       sample  205783   4.662 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.502           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.014           ms/op
