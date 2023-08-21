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
# Warmup Iteration   1: 1.267 ops/ms
# Warmup Iteration   2: 3.253 ops/ms
# Warmup Iteration   3: 5.788 ops/ms
Iteration   1: 6.201 ops/ms
Iteration   2: 6.117 ops/ms
Iteration   3: 6.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.206 ±(99.9%) 1.662 ops/ms [Average]
  (min, avg, max) = (6.117, 6.206, 6.299), stdev = 0.091
  CI (99.9%): [4.544, 7.868] (assumes normal distribution)


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
# Warmup Iteration   1: 1.957 ops/ms
# Warmup Iteration   2: 5.427 ops/ms
# Warmup Iteration   3: 6.426 ops/ms
Iteration   1: 6.447 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.648 ±(99.9%) 3.224 ops/ms [Average]
  (min, avg, max) = (6.447, 6.648, 6.777), stdev = 0.177
  CI (99.9%): [3.425, 9.872] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.991 ops/ms
# Warmup Iteration   2: 5.184 ops/ms
# Warmup Iteration   3: 6.353 ops/ms
Iteration   1: 6.260 ops/ms
Iteration   2: 5.906 ops/ms
Iteration   3: 6.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.127 ±(99.9%) 3.515 ops/ms [Average]
  (min, avg, max) = (5.906, 6.127, 6.260), stdev = 0.193
  CI (99.9%): [2.612, 9.642] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.778 ops/ms
# Warmup Iteration   2: 4.682 ops/ms
# Warmup Iteration   3: 5.208 ops/ms
Iteration   1: 5.267 ops/ms
Iteration   2: 5.513 ops/ms
Iteration   3: 5.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.411 ±(99.9%) 2.333 ops/ms [Average]
  (min, avg, max) = (5.267, 5.411, 5.513), stdev = 0.128
  CI (99.9%): [3.077, 7.744] (assumes normal distribution)


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
# Warmup Iteration   1: 15.499 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.668 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.671 ±(99.9%) 0.005 ms/op
Iteration   1: 5.104 ±(99.9%) 0.015 ms/op
Iteration   2: 5.295 ±(99.9%) 0.007 ms/op
Iteration   3: 5.145 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.181 ±(99.9%) 1.832 ms/op [Average]
  (min, avg, max) = (5.104, 5.181, 5.295), stdev = 0.100
  CI (99.9%): [3.349, 7.013] (assumes normal distribution)


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
# Warmup Iteration   1: 14.643 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.370 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.924 ±(99.9%) 0.011 ms/op
Iteration   1: 4.979 ±(99.9%) 0.006 ms/op
Iteration   2: 4.812 ±(99.9%) 0.010 ms/op
Iteration   3: 4.829 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.873 ±(99.9%) 1.675 ms/op [Average]
  (min, avg, max) = (4.812, 4.873, 4.979), stdev = 0.092
  CI (99.9%): [3.198, 6.548] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.342 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.458 ±(99.9%) 0.009 ms/op
Iteration   1: 5.252 ±(99.9%) 0.009 ms/op
Iteration   2: 5.203 ±(99.9%) 0.008 ms/op
Iteration   3: 5.219 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.225 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (5.203, 5.225, 5.252), stdev = 0.025
  CI (99.9%): [4.763, 5.686] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 17.167 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.693 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 6.003 ±(99.9%) 0.013 ms/op
Iteration   1: 5.786 ±(99.9%) 0.017 ms/op
Iteration   2: 5.931 ±(99.9%) 0.019 ms/op
Iteration   3: 6.020 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.912 ±(99.9%) 2.157 ms/op [Average]
  (min, avg, max) = (5.786, 5.912, 6.020), stdev = 0.118
  CI (99.9%): [3.755, 8.069] (assumes normal distribution)


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
# Warmup Iteration   1: 15.896 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.780 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.683 ±(99.9%) 0.025 ms/op
Iteration   1: 5.311 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.537 ms/op
                 createUser·p0.99:   9.847 ms/op
                 createUser·p0.999:  19.492 ms/op
                 createUser·p0.9999: 25.164 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 5.210 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   6.930 ms/op
                 createUser·p0.99:   9.748 ms/op
                 createUser·p0.999:  21.143 ms/op
                 createUser·p0.9999: 25.578 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 4.992 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.089 ms/op
                 createUser·p0.50:   4.768 ms/op
                 createUser·p0.90:   5.833 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   9.404 ms/op
                 createUser·p0.999:  25.887 ms/op
                 createUser·p0.9999: 44.316 ms/op
                 createUser·p1.00:   45.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185486
  mean =      5.167 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 102590 
    [ 5.000, 10.000) = 81242 
    [10.000, 15.000) = 1206 
    [15.000, 20.000) = 199 
    [20.000, 25.000) = 140 
    [25.000, 30.000) = 97 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     22.659 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     45.052 ms/op
     p(99.9999) =     45.220 ms/op
    p(100.0000) =     45.220 ms/op


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
# Warmup Iteration   1: 15.399 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 5.733 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.154 ±(99.9%) 0.017 ms/op
Iteration   1: 4.960 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.028 ms/op
                 existUser·p0.50:   4.743 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.562 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  20.262 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 4.963 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.159 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   8.949 ms/op
                 existUser·p0.999:  18.429 ms/op
                 existUser·p0.9999: 25.708 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 4.998 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   9.550 ms/op
                 existUser·p0.999:  24.652 ms/op
                 existUser·p0.9999: 28.855 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 192964
  mean =      4.973 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 128704 
    [ 5.000,  7.500) = 57682 
    [ 7.500, 10.000) = 5155 
    [10.000, 12.500) = 896 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      2.028 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     20.468 ms/op
     p(99.9900) =     28.377 ms/op
     p(99.9990) =     29.037 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 15.283 ±(99.9%) 0.216 ms/op
# Warmup Iteration   2: 5.840 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.207 ±(99.9%) 0.017 ms/op
Iteration   1: 5.241 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   8.135 ms/op
                 getUser·p0.99:   11.068 ms/op
                 getUser·p0.999:  20.934 ms/op
                 getUser·p0.9999: 24.995 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 5.100 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.232 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   7.201 ms/op
                 getUser·p0.99:   9.830 ms/op
                 getUser·p0.999:  23.995 ms/op
                 getUser·p0.9999: 27.334 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   3: 5.148 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.701 ms/op
                 getUser·p0.99:   9.830 ms/op
                 getUser·p0.999:  26.018 ms/op
                 getUser·p0.9999: 31.705 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186030
  mean =      5.162 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 106273 
    [ 5.000,  7.500) = 70743 
    [ 7.500, 10.000) = 6842 
    [10.000, 12.500) = 1323 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.029 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     10.317 ms/op
     p(99.9000) =     21.482 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     31.855 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 16.280 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 7.094 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.110 ±(99.9%) 0.023 ms/op
Iteration   1: 6.126 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.138 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.324 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.550 ms/op
                 listUser·p0.999:  24.838 ms/op
                 listUser·p0.9999: 29.301 ms/op
                 listUser·p1.00:   29.884 ms/op

Iteration   2: 6.265 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.986 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.010 ms/op
                 listUser·p0.999:  25.556 ms/op
                 listUser·p0.9999: 32.715 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.028 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.808 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   8.004 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  21.037 ms/op
                 listUser·p0.9999: 23.583 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156343
  mean =      6.138 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 12210 
    [ 5.000,  7.500) = 130130 
    [ 7.500, 10.000) = 10456 
    [10.000, 12.500) = 2223 
    [12.500, 15.000) = 751 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.808 ms/op
     p(50.0000) =      5.816 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     31.142 ms/op
     p(99.9990) =     34.351 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.206 ± 1.662  ops/ms
ClientPb.existUser                       thrpt       3   6.648 ± 3.224  ops/ms
ClientPb.getUser                         thrpt       3   6.127 ± 3.515  ops/ms
ClientPb.listUser                        thrpt       3   5.411 ± 2.333  ops/ms
ClientPb.createUser                       avgt       3   5.181 ± 1.832   ms/op
ClientPb.existUser                        avgt       3   4.873 ± 1.675   ms/op
ClientPb.getUser                          avgt       3   5.225 ± 0.461   ms/op
ClientPb.listUser                         avgt       3   5.912 ± 2.157   ms/op
ClientPb.createUser                     sample  185486   5.167 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.653           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.053           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.732           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.659           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.327           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.220           ms/op
ClientPb.existUser                      sample  192964   4.973 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.322           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.377           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.098           ms/op
ClientPb.getUser                        sample  186030   5.162 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.911           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.406           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.317           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.482           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.753           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  156343   6.138 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.075           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.626           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.142           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.717           ms/op
