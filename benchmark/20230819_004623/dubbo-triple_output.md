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
# Warmup Iteration   1: 2.337 ops/ms
# Warmup Iteration   2: 6.264 ops/ms
# Warmup Iteration   3: 8.895 ops/ms
Iteration   1: 9.513 ops/ms
Iteration   2: 9.483 ops/ms
Iteration   3: 9.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.506 ±(99.9%) 0.378 ops/ms [Average]
  (min, avg, max) = (9.483, 9.506, 9.522), stdev = 0.021
  CI (99.9%): [9.128, 9.883] (assumes normal distribution)


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
# Warmup Iteration   1: 3.148 ops/ms
# Warmup Iteration   2: 8.713 ops/ms
# Warmup Iteration   3: 9.390 ops/ms
Iteration   1: 10.121 ops/ms
Iteration   2: 10.371 ops/ms
Iteration   3: 10.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.189 ±(99.9%) 2.911 ops/ms [Average]
  (min, avg, max) = (10.075, 10.189, 10.371), stdev = 0.160
  CI (99.9%): [7.278, 13.100] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.385 ops/ms
# Warmup Iteration   2: 8.639 ops/ms
# Warmup Iteration   3: 9.371 ops/ms
Iteration   1: 9.786 ops/ms
Iteration   2: 10.194 ops/ms
Iteration   3: 9.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.954 ±(99.9%) 3.895 ops/ms [Average]
  (min, avg, max) = (9.786, 9.954, 10.194), stdev = 0.213
  CI (99.9%): [6.059, 13.849] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 7.284 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 8.225 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 8.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.216 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (8.057, 8.216, 8.367), stdev = 0.155
  CI (99.9%): [5.388, 11.044] (assumes normal distribution)


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
# Warmup Iteration   1: 8.304 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.004 ms/op
Iteration   1: 3.318 ±(99.9%) 0.006 ms/op
Iteration   2: 3.246 ±(99.9%) 0.003 ms/op
Iteration   3: 3.214 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (3.214, 3.260, 3.318), stdev = 0.053
  CI (99.9%): [2.287, 4.233] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.858 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.221 ±(99.9%) 0.004 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.108 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.147 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (3.108, 3.147, 3.221), stdev = 0.064
  CI (99.9%): [1.984, 4.311] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.210 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.005 ms/op
Iteration   1: 3.180 ±(99.9%) 0.007 ms/op
Iteration   2: 3.367 ±(99.9%) 0.004 ms/op
Iteration   3: 3.260 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.269 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (3.180, 3.269, 3.367), stdev = 0.094
  CI (99.9%): [1.561, 4.976] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.645 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.008 ms/op
Iteration   1: 3.776 ±(99.9%) 0.009 ms/op
Iteration   2: 3.742 ±(99.9%) 0.009 ms/op
Iteration   3: 3.763 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.761 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.742, 3.761, 3.776), stdev = 0.017
  CI (99.9%): [3.445, 4.076] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.788 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.010 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  14.449 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.349 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.469 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  19.054 ms/op
                 createUser·p0.9999: 27.620 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.240 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  15.373 ms/op
                 createUser·p0.9999: 28.578 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292238
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21793 
    [ 2.500,  5.000) = 262639 
    [ 5.000,  7.500) = 6438 
    [ 7.500, 10.000) = 934 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     28.042 ms/op
     p(99.9990) =     28.937 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.551 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
Iteration   1: 3.168 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 23.131 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 3.207 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  12.326 ms/op
                 existUser·p0.9999: 29.427 ms/op
                 existUser·p1.00:   30.540 ms/op

Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.770 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 22.258 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302650
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25648 
    [ 2.500,  5.000) = 269069 
    [ 5.000,  7.500) = 6589 
    [ 7.500, 10.000) = 957 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     11.589 ms/op
     p(99.9900) =     28.131 ms/op
     p(99.9990) =     30.505 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 8.073 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.011 ms/op
Iteration   1: 3.308 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  13.756 ms/op
                 getUser·p0.9999: 26.422 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   2: 3.385 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.931 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  18.826 ms/op
                 getUser·p0.9999: 27.117 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.327 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.408 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  17.400 ms/op
                 getUser·p0.9999: 26.317 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287373
  mean =      3.340 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21168 
    [ 2.500,  5.000) = 254875 
    [ 5.000,  7.500) = 9712 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     17.322 ms/op
     p(99.9900) =     26.583 ms/op
     p(99.9990) =     27.854 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 8.921 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.013 ms/op
Iteration   1: 3.829 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  17.938 ms/op
                 listUser·p0.9999: 22.500 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.886 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  13.493 ms/op
                 listUser·p0.9999: 14.795 ms/op
                 listUser·p1.00:   15.057 ms/op

Iteration   3: 3.800 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.229 ms/op
                 listUser·p0.999:  13.447 ms/op
                 listUser·p0.9999: 16.801 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250260
  mean =      3.838 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 240776 
    [ 5.000,  7.500) = 6784 
    [ 7.500, 10.000) = 1810 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 387 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.506 ± 0.378  ops/ms
ClientPb.existUser                       thrpt       3  10.189 ± 2.911  ops/ms
ClientPb.getUser                         thrpt       3   9.954 ± 3.895  ops/ms
ClientPb.listUser                        thrpt       3   8.216 ± 2.828  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 0.973   ms/op
ClientPb.existUser                        avgt       3   3.147 ± 1.163   ms/op
ClientPb.getUser                          avgt       3   3.269 ± 1.708   ms/op
ClientPb.listUser                         avgt       3   3.761 ± 0.315   ms/op
ClientPb.createUser                     sample  292238   3.282 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.469           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.664           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.032           ms/op
ClientPb.existUser                      sample  302650   3.172 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.949           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.054           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.589           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.540           ms/op
ClientPb.getUser                        sample  287373   3.340 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.408           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.322           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.583           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.606           ms/op
ClientPb.listUser                       sample  250260   3.838 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.401           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.037           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
