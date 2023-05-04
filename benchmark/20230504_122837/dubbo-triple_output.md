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
# Warmup Iteration   1: 2.774 ops/ms
# Warmup Iteration   2: 6.588 ops/ms
# Warmup Iteration   3: 9.177 ops/ms
Iteration   1: 10.003 ops/ms
Iteration   2: 9.941 ops/ms
Iteration   3: 9.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.981 ±(99.9%) 0.630 ops/ms [Average]
  (min, avg, max) = (9.941, 9.981, 10.003), stdev = 0.035
  CI (99.9%): [9.352, 10.611] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ops/ms
# Warmup Iteration   2: 9.068 ops/ms
# Warmup Iteration   3: 10.439 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.179 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.438 ±(99.9%) 4.344 ops/ms [Average]
  (min, avg, max) = (10.179, 10.438, 10.648), stdev = 0.238
  CI (99.9%): [6.094, 14.782] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 9.497 ops/ms
# Warmup Iteration   3: 9.571 ops/ms
Iteration   1: 9.896 ops/ms
Iteration   2: 9.818 ops/ms
Iteration   3: 9.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.840 ±(99.9%) 0.884 ops/ms [Average]
  (min, avg, max) = (9.807, 9.840, 9.896), stdev = 0.048
  CI (99.9%): [8.956, 10.724] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.422 ops/ms
# Warmup Iteration   2: 7.953 ops/ms
# Warmup Iteration   3: 8.507 ops/ms
Iteration   1: 8.368 ops/ms
Iteration   2: 8.730 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.531 ±(99.9%) 3.351 ops/ms [Average]
  (min, avg, max) = (8.368, 8.531, 8.730), stdev = 0.184
  CI (99.9%): [5.180, 11.883] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.233 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.004 ms/op
Iteration   1: 3.159 ±(99.9%) 0.002 ms/op
Iteration   2: 3.067 ±(99.9%) 0.004 ms/op
Iteration   3: 3.345 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.190 ±(99.9%) 2.590 ms/op [Average]
  (min, avg, max) = (3.067, 3.190, 3.345), stdev = 0.142
  CI (99.9%): [0.600, 5.780] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.292 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.004 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
Iteration   3: 3.176 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.098 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.050, 3.098, 3.176), stdev = 0.069
  CI (99.9%): [1.847, 4.348] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.411 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.003 ms/op
Iteration   1: 3.189 ±(99.9%) 0.008 ms/op
Iteration   2: 3.286 ±(99.9%) 0.002 ms/op
Iteration   3: 3.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.227 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (3.189, 3.227, 3.286), stdev = 0.052
  CI (99.9%): [2.278, 4.176] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.005 ms/op
Iteration   1: 3.739 ±(99.9%) 0.007 ms/op
Iteration   2: 3.678 ±(99.9%) 0.011 ms/op
Iteration   3: 3.602 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.673 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.602, 3.673, 3.739), stdev = 0.069
  CI (99.9%): [2.415, 4.931] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.372 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
Iteration   1: 3.136 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  20.087 ms/op
                 createUser·p0.9999: 25.061 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  15.916 ms/op
                 createUser·p0.9999: 27.210 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  15.323 ms/op
                 createUser·p0.9999: 32.866 ms/op
                 createUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299810
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17958 
    [ 2.500,  5.000) = 277515 
    [ 5.000,  7.500) = 3468 
    [ 7.500, 10.000) = 294 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     16.275 ms/op
     p(99.9900) =     31.850 ms/op
     p(99.9990) =     33.030 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.728 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.148 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  14.643 ms/op
                 existUser·p0.9999: 24.986 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  13.943 ms/op
                 existUser·p0.9999: 22.041 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.109 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  7.987 ms/op
                 existUser·p0.9999: 18.662 ms/op
                 existUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315809
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27022 
    [ 2.500,  5.000) = 284260 
    [ 5.000,  7.500) = 3786 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.203 ms/op
     p(95.0000) =      3.445 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     23.435 ms/op
     p(99.9990) =     25.980 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.255 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.011 ms/op
Iteration   1: 3.260 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 21.738 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  11.960 ms/op
                 getUser·p0.9999: 27.525 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.207 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 28.250 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300318
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16630 
    [ 2.500,  5.000) = 276539 
    [ 5.000,  7.500) = 6315 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     27.324 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.559 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.014 ms/op
Iteration   1: 3.694 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.530 ms/op
                 listUser·p0.9999: 18.471 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 3.664 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.316 ms/op
                 listUser·p0.9999: 14.205 ms/op
                 listUser·p1.00:   14.270 ms/op

Iteration   3: 3.791 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.141 ms/op
                 listUser·p0.999:  12.261 ms/op
                 listUser·p0.9999: 13.042 ms/op
                 listUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258168
  mean =      3.715 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 91 
    [ 2.500,  3.750) = 184782 
    [ 3.750,  5.000) = 66398 
    [ 5.000,  6.250) = 2067 
    [ 6.250,  7.500) = 3269 
    [ 7.500,  8.750) = 752 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 238 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     17.424 ms/op
     p(99.9990) =     19.407 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.981 ± 0.630  ops/ms
ClientPb.existUser                       thrpt       3  10.438 ± 4.344  ops/ms
ClientPb.getUser                         thrpt       3   9.840 ± 0.884  ops/ms
ClientPb.listUser                        thrpt       3   8.531 ± 3.351  ops/ms
ClientPb.createUser                       avgt       3   3.190 ± 2.590   ms/op
ClientPb.existUser                        avgt       3   3.098 ± 1.251   ms/op
ClientPb.getUser                          avgt       3   3.227 ± 0.949   ms/op
ClientPb.listUser                         avgt       3   3.673 ± 1.258   ms/op
ClientPb.createUser                     sample  299810   3.198 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.198           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.275           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.850           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.161           ms/op
ClientPb.existUser                      sample  315809   3.037 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.829           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  300318   3.196 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.908           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.324           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  258168   3.715 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.592           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.685           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.452           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.424           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.694           ms/op
