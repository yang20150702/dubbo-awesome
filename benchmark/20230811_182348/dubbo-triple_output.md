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
# Warmup Iteration   1: 1.183 ops/ms
# Warmup Iteration   2: 2.551 ops/ms
# Warmup Iteration   3: 5.440 ops/ms
Iteration   1: 6.226 ops/ms
Iteration   2: 6.255 ops/ms
Iteration   3: 7.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.518 ±(99.9%) 8.784 ops/ms [Average]
  (min, avg, max) = (6.226, 6.518, 7.074), stdev = 0.482
  CI (99.9%): [≈ 0, 15.303] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.086 ops/ms
# Warmup Iteration   2: 5.932 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.502 ops/ms
Iteration   2: 6.919 ops/ms
Iteration   3: 7.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.333 ±(99.9%) 6.572 ops/ms [Average]
  (min, avg, max) = (6.919, 7.333, 7.577), stdev = 0.360
  CI (99.9%): [0.761, 13.905] (assumes normal distribution)


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
# Warmup Iteration   1: 2.005 ops/ms
# Warmup Iteration   2: 5.856 ops/ms
# Warmup Iteration   3: 7.495 ops/ms
Iteration   1: 7.037 ops/ms
Iteration   2: 6.585 ops/ms
Iteration   3: 7.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.032 ±(99.9%) 8.109 ops/ms [Average]
  (min, avg, max) = (6.585, 7.032, 7.474), stdev = 0.444
  CI (99.9%): [≈ 0, 15.141] (assumes normal distribution)


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
# Warmup Iteration   1: 1.868 ops/ms
# Warmup Iteration   2: 4.802 ops/ms
# Warmup Iteration   3: 6.165 ops/ms
Iteration   1: 6.227 ops/ms
Iteration   2: 6.519 ops/ms
Iteration   3: 5.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.245 ±(99.9%) 4.837 ops/ms [Average]
  (min, avg, max) = (5.990, 6.245, 6.519), stdev = 0.265
  CI (99.9%): [1.409, 11.082] (assumes normal distribution)


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
# Warmup Iteration   1: 14.603 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.009 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.055 ±(99.9%) 0.008 ms/op
Iteration   1: 4.687 ±(99.9%) 0.007 ms/op
Iteration   2: 4.552 ±(99.9%) 0.014 ms/op
Iteration   3: 4.270 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.503 ±(99.9%) 3.879 ms/op [Average]
  (min, avg, max) = (4.270, 4.503, 4.687), stdev = 0.213
  CI (99.9%): [0.625, 8.382] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.228 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.400 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.013 ms/op
Iteration   1: 3.848 ±(99.9%) 0.003 ms/op
Iteration   2: 3.978 ±(99.9%) 0.003 ms/op
Iteration   3: 4.238 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.021 ±(99.9%) 3.620 ms/op [Average]
  (min, avg, max) = (3.848, 4.021, 4.238), stdev = 0.198
  CI (99.9%): [0.402, 7.641] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.179 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.372 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.645 ±(99.9%) 0.008 ms/op
Iteration   1: 4.146 ±(99.9%) 0.007 ms/op
Iteration   2: 4.212 ±(99.9%) 0.007 ms/op
Iteration   3: 4.516 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.292 ±(99.9%) 3.604 ms/op [Average]
  (min, avg, max) = (4.146, 4.292, 4.516), stdev = 0.198
  CI (99.9%): [0.688, 7.895] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.694 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.139 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.636 ±(99.9%) 0.014 ms/op
Iteration   1: 5.148 ±(99.9%) 0.009 ms/op
Iteration   2: 4.895 ±(99.9%) 0.013 ms/op
Iteration   3: 5.200 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.081 ±(99.9%) 2.980 ms/op [Average]
  (min, avg, max) = (4.895, 5.081, 5.200), stdev = 0.163
  CI (99.9%): [2.101, 8.062] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.283 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 6.315 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.683 ±(99.9%) 0.033 ms/op
Iteration   1: 4.703 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   6.914 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  26.150 ms/op
                 createUser·p0.9999: 36.176 ms/op
                 createUser·p1.00:   36.897 ms/op

Iteration   2: 4.653 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.857 ms/op
                 createUser·p0.95:   6.734 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  24.486 ms/op
                 createUser·p0.9999: 31.986 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   3: 5.008 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.060 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.430 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  30.179 ms/op
                 createUser·p0.9999: 38.851 ms/op
                 createUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 200684
  mean =      4.783 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 172 
    [ 2.500,  5.000) = 139392 
    [ 5.000,  7.500) = 53765 
    [ 7.500, 10.000) = 5186 
    [10.000, 12.500) = 1348 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     26.126 ms/op
     p(99.9900) =     37.417 ms/op
     p(99.9990) =     39.321 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.316 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 4.931 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.016 ms/op
Iteration   1: 4.601 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.808 ms/op
                 existUser·p0.50:   4.293 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.709 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  16.176 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 4.513 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.628 ms/op
                 existUser·p0.95:   6.332 ms/op
                 existUser·p0.99:   9.175 ms/op
                 existUser·p0.999:  20.972 ms/op
                 existUser·p0.9999: 25.879 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 4.209 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   6.463 ms/op
                 existUser·p0.99:   8.868 ms/op
                 existUser·p0.999:  15.681 ms/op
                 existUser·p0.9999: 26.686 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 216271
  mean =      4.435 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 291 
    [ 2.500,  5.000) = 173798 
    [ 5.000,  7.500) = 37063 
    [ 7.500, 10.000) = 3595 
    [10.000, 12.500) = 916 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     19.208 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.909 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.006 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.683 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.136 ±(99.9%) 0.028 ms/op
Iteration   1: 5.071 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.417 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.126 ms/op
                 getUser·p0.99:   11.583 ms/op
                 getUser·p0.999:  26.292 ms/op
                 getUser·p0.9999: 37.608 ms/op
                 getUser·p1.00:   40.174 ms/op

Iteration   2: 4.777 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.436 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   6.216 ms/op
                 getUser·p0.95:   7.266 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  28.213 ms/op
                 getUser·p0.9999: 30.187 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   3: 4.708 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   6.832 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 38.863 ms/op
                 getUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 197934
  mean =      4.847 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 139430 
    [ 5.000, 10.000) = 55771 
    [10.000, 15.000) = 2323 
    [15.000, 20.000) = 144 
    [20.000, 25.000) = 42 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 60 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     27.368 ms/op
     p(99.9900) =     37.566 ms/op
     p(99.9990) =     39.211 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


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
# Warmup Iteration   1: 14.695 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 6.508 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.863 ±(99.9%) 0.025 ms/op
Iteration   1: 5.295 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.726 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   10.863 ms/op
                 listUser·p0.999:  28.213 ms/op
                 listUser·p0.9999: 35.652 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   2: 4.753 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  22.470 ms/op
                 listUser·p0.9999: 30.638 ms/op
                 listUser·p1.00:   31.818 ms/op

Iteration   3: 5.141 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.823 ms/op
                 listUser·p0.99:   11.436 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 19.974 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 189872
  mean =      5.053 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 137847 
    [ 5.000,  7.500) = 43072 
    [ 7.500, 10.000) = 6226 
    [10.000, 12.500) = 1874 
    [12.500, 15.000) = 380 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.901 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     24.068 ms/op
     p(99.9900) =     33.557 ms/op
     p(99.9990) =     36.163 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.518 ± 8.784  ops/ms
ClientPb.existUser                       thrpt       3   7.333 ± 6.572  ops/ms
ClientPb.getUser                         thrpt       3   7.032 ± 8.109  ops/ms
ClientPb.listUser                        thrpt       3   6.245 ± 4.837  ops/ms
ClientPb.createUser                       avgt       3   4.503 ± 3.879   ms/op
ClientPb.existUser                        avgt       3   4.021 ± 3.620   ms/op
ClientPb.getUser                          avgt       3   4.292 ± 3.604   ms/op
ClientPb.listUser                         avgt       3   5.081 ± 2.980   ms/op
ClientPb.createUser                     sample  200684   4.783 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.936           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.053           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.191           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.126           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.417           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.387           ms/op
ClientPb.existUser                      sample  216271   4.435 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.620           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.208           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.083           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.099           ms/op
ClientPb.getUser                        sample  197934   4.847 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.436           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.813           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.368           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.174           ms/op
ClientPb.listUser                       sample  189872   5.053 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.781           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.068           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.557           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.635           ms/op
