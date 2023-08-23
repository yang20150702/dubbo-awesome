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
# Warmup Iteration   1: 2.474 ops/ms
# Warmup Iteration   2: 5.772 ops/ms
# Warmup Iteration   3: 9.282 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 9.428 ops/ms
Iteration   3: 9.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.483 ±(99.9%) 3.148 ops/ms [Average]
  (min, avg, max) = (9.344, 9.483, 9.676), stdev = 0.173
  CI (99.9%): [6.335, 12.631] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.495 ops/ms
# Warmup Iteration   2: 9.186 ops/ms
# Warmup Iteration   3: 9.986 ops/ms
Iteration   1: 9.818 ops/ms
Iteration   2: 10.063 ops/ms
Iteration   3: 9.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.862 ±(99.9%) 3.334 ops/ms [Average]
  (min, avg, max) = (9.705, 9.862, 10.063), stdev = 0.183
  CI (99.9%): [6.528, 13.196] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 8.568 ops/ms
# Warmup Iteration   3: 9.180 ops/ms
Iteration   1: 9.626 ops/ms
Iteration   2: 9.739 ops/ms
Iteration   3: 9.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.622 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (9.501, 9.622, 9.739), stdev = 0.119
  CI (99.9%): [7.451, 11.793] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 7.700 ops/ms
# Warmup Iteration   3: 8.142 ops/ms
Iteration   1: 8.286 ops/ms
Iteration   2: 8.260 ops/ms
Iteration   3: 8.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.312 ±(99.9%) 1.235 ops/ms [Average]
  (min, avg, max) = (8.260, 8.312, 8.388), stdev = 0.068
  CI (99.9%): [7.077, 9.547] (assumes normal distribution)


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
# Warmup Iteration   1: 8.750 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.004 ms/op
Iteration   1: 3.270 ±(99.9%) 0.005 ms/op
Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
Iteration   3: 3.267 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.254 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.224, 3.254, 3.270), stdev = 0.026
  CI (99.9%): [2.785, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 8.254 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.004 ms/op
Iteration   1: 3.275 ±(99.9%) 0.005 ms/op
Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
Iteration   3: 3.184 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.186 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (3.098, 3.186, 3.275), stdev = 0.088
  CI (99.9%): [1.577, 4.794] (assumes normal distribution)


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
# Warmup Iteration   1: 8.639 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.004 ms/op
Iteration   1: 3.299 ±(99.9%) 0.001 ms/op
Iteration   2: 3.255 ±(99.9%) 0.003 ms/op
Iteration   3: 3.354 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.302 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (3.255, 3.302, 3.354), stdev = 0.050
  CI (99.9%): [2.397, 4.207] (assumes normal distribution)


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
# Warmup Iteration   1: 9.203 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.004 ms/op
Iteration   1: 3.820 ±(99.9%) 0.007 ms/op
Iteration   2: 3.755 ±(99.9%) 0.007 ms/op
Iteration   3: 3.747 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.774 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.747, 3.774, 3.820), stdev = 0.040
  CI (99.9%): [3.040, 4.507] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.034 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.010 ms/op
Iteration   1: 3.283 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 20.980 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  19.714 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 25.199 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293201
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18337 
    [ 2.500,  5.000) = 268819 
    [ 5.000,  7.500) = 4777 
    [ 7.500, 10.000) = 800 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     25.090 ms/op
     p(99.9990) =     26.187 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 7.377 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
Iteration   1: 3.121 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  15.068 ms/op
                 existUser·p0.9999: 19.415 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  16.777 ms/op
                 existUser·p0.9999: 23.484 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.199 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303543
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15068 
    [ 2.500,  5.000) = 282104 
    [ 5.000,  7.500) = 4654 
    [ 7.500, 10.000) = 1085 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     15.397 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.984 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 8.310 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.012 ms/op
Iteration   1: 3.330 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  18.332 ms/op
                 getUser·p0.9999: 21.233 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.414 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  18.312 ms/op
                 getUser·p0.9999: 25.887 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.447 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  15.511 ms/op
                 getUser·p0.9999: 23.617 ms/op
                 getUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282543
  mean =      3.396 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19778 
    [ 2.500,  5.000) = 251097 
    [ 5.000,  7.500) = 9972 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     16.406 ms/op
     p(99.9900) =     25.387 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 8.660 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.012 ms/op
Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.607 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 3.818 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  12.569 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 3.841 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.888 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251568
  mean =      3.814 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 240963 
    [ 5.000,  7.500) = 7744 
    [ 7.500, 10.000) = 1962 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     14.065 ms/op
     p(99.9900) =     20.278 ms/op
     p(99.9990) =     21.839 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.483 ± 3.148  ops/ms
ClientPb.existUser                       thrpt       3   9.862 ± 3.334  ops/ms
ClientPb.getUser                         thrpt       3   9.622 ± 2.171  ops/ms
ClientPb.listUser                        thrpt       3   8.312 ± 1.235  ops/ms
ClientPb.createUser                       avgt       3   3.254 ± 0.469   ms/op
ClientPb.existUser                        avgt       3   3.186 ± 1.609   ms/op
ClientPb.getUser                          avgt       3   3.302 ± 0.905   ms/op
ClientPb.listUser                         avgt       3   3.774 ± 0.733   ms/op
ClientPb.createUser                     sample  293201   3.276 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.679           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.071           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.968           ms/op
ClientPb.existUser                      sample  303543   3.161 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.967           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.397           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.741           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.264           ms/op
ClientPb.getUser                        sample  282543   3.396 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.406           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.387           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.608           ms/op
ClientPb.listUser                       sample  251568   3.814 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.933           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.065           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.278           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.955           ms/op
