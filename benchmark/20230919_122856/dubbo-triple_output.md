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
# Warmup Iteration   1: 2.272 ops/ms
# Warmup Iteration   2: 6.125 ops/ms
# Warmup Iteration   3: 8.446 ops/ms
Iteration   1: 8.954 ops/ms
Iteration   2: 9.322 ops/ms
Iteration   3: 9.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.230 ±(99.9%) 4.431 ops/ms [Average]
  (min, avg, max) = (8.954, 9.230, 9.413), stdev = 0.243
  CI (99.9%): [4.799, 13.661] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.145 ops/ms
# Warmup Iteration   2: 9.097 ops/ms
# Warmup Iteration   3: 9.471 ops/ms
Iteration   1: 9.770 ops/ms
Iteration   2: 9.711 ops/ms
Iteration   3: 9.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.686 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (9.577, 9.686, 9.770), stdev = 0.099
  CI (99.9%): [7.880, 11.492] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ops/ms
# Warmup Iteration   2: 8.626 ops/ms
# Warmup Iteration   3: 9.069 ops/ms
Iteration   1: 9.047 ops/ms
Iteration   2: 9.121 ops/ms
Iteration   3: 9.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.115 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (9.047, 9.115, 9.175), stdev = 0.064
  CI (99.9%): [7.946, 10.283] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.840 ops/ms
# Warmup Iteration   2: 6.947 ops/ms
# Warmup Iteration   3: 7.520 ops/ms
Iteration   1: 7.741 ops/ms
Iteration   2: 7.670 ops/ms
Iteration   3: 7.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.700 ±(99.9%) 0.673 ops/ms [Average]
  (min, avg, max) = (7.670, 7.700, 7.741), stdev = 0.037
  CI (99.9%): [7.028, 8.373] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.221 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.006 ms/op
Iteration   1: 3.467 ±(99.9%) 0.004 ms/op
Iteration   2: 3.375 ±(99.9%) 0.004 ms/op
Iteration   3: 3.343 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.395 ±(99.9%) 1.178 ms/op [Average]
  (min, avg, max) = (3.343, 3.395, 3.467), stdev = 0.065
  CI (99.9%): [2.216, 4.573] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.632 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.005 ms/op
Iteration   1: 3.410 ±(99.9%) 0.004 ms/op
Iteration   2: 3.279 ±(99.9%) 0.004 ms/op
Iteration   3: 3.290 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.326 ±(99.9%) 1.326 ms/op [Average]
  (min, avg, max) = (3.279, 3.326, 3.410), stdev = 0.073
  CI (99.9%): [2.000, 4.652] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.241 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.004 ms/op
Iteration   1: 3.399 ±(99.9%) 0.004 ms/op
Iteration   2: 3.430 ±(99.9%) 0.004 ms/op
Iteration   3: 3.413 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.414 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.399, 3.414, 3.430), stdev = 0.015
  CI (99.9%): [3.137, 3.691] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.969 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.006 ms/op
Iteration   1: 4.038 ±(99.9%) 0.006 ms/op
Iteration   2: 4.058 ±(99.9%) 0.006 ms/op
Iteration   3: 4.054 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.050 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (4.038, 4.050, 4.058), stdev = 0.011
  CI (99.9%): [3.853, 4.246] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.159 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.918 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  20.854 ms/op
                 createUser·p0.9999: 24.174 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.536 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.781 ms/op
                 createUser·p0.999:  22.605 ms/op
                 createUser·p0.9999: 31.061 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276584
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4467 
    [ 2.500,  5.000) = 266116 
    [ 5.000,  7.500) = 4733 
    [ 7.500, 10.000) = 583 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 183 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     20.887 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 8.545 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.009 ms/op
Iteration   1: 3.320 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  18.282 ms/op
                 existUser·p0.9999: 24.052 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.342 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  22.100 ms/op
                 existUser·p0.9999: 25.555 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 28.439 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287503
  mean =      3.335 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7978 
    [ 2.500,  5.000) = 273660 
    [ 5.000,  7.500) = 4436 
    [ 7.500, 10.000) = 656 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 179 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     26.714 ms/op
     p(99.9990) =     29.041 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 8.711 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.011 ms/op
Iteration   1: 3.538 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  13.100 ms/op
                 getUser·p0.9999: 23.231 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.573 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  24.133 ms/op
                 getUser·p0.9999: 29.524 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.802 ms/op
                 getUser·p0.999:  22.540 ms/op
                 getUser·p0.9999: 27.813 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271992
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6395 
    [ 2.500,  5.000) = 255968 
    [ 5.000,  7.500) = 8264 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     27.879 ms/op
     p(99.9990) =     29.992 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 9.744 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.566 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.013 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  20.101 ms/op
                 listUser·p0.9999: 24.486 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 4.138 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  16.133 ms/op
                 listUser·p0.9999: 26.391 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 4.024 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.998 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 20.320 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234398
  mean =      4.096 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 226358 
    [ 5.000,  7.500) = 6029 
    [ 7.500, 10.000) = 1181 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     24.041 ms/op
     p(99.9990) =     27.350 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.230 ± 4.431  ops/ms
ClientPb.existUser                       thrpt       3   9.686 ± 1.806  ops/ms
ClientPb.getUser                         thrpt       3   9.115 ± 1.168  ops/ms
ClientPb.listUser                        thrpt       3   7.700 ± 0.673  ops/ms
ClientPb.createUser                       avgt       3   3.395 ± 1.178   ms/op
ClientPb.existUser                        avgt       3   3.326 ± 1.326   ms/op
ClientPb.getUser                          avgt       3   3.414 ± 0.277   ms/op
ClientPb.listUser                         avgt       3   4.050 ± 0.196   ms/op
ClientPb.createUser                     sample  276584   3.471 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.029           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.887           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.394           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  287503   3.335 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.190           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.991           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.714           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.655           ms/op
ClientPb.getUser                        sample  271992   3.528 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.930           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.879           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  234398   4.096 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.415           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.810           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.041           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
