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
# Warmup Iteration   1: 2.453 ops/ms
# Warmup Iteration   2: 5.627 ops/ms
# Warmup Iteration   3: 9.239 ops/ms
Iteration   1: 9.570 ops/ms
Iteration   2: 9.275 ops/ms
Iteration   3: 9.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.532 ±(99.9%) 4.377 ops/ms [Average]
  (min, avg, max) = (9.275, 9.532, 9.750), stdev = 0.240
  CI (99.9%): [5.154, 13.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.374 ops/ms
# Warmup Iteration   2: 9.508 ops/ms
# Warmup Iteration   3: 9.572 ops/ms
Iteration   1: 10.064 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.232 ±(99.9%) 3.682 ops/ms [Average]
  (min, avg, max) = (10.064, 10.232, 10.456), stdev = 0.202
  CI (99.9%): [6.550, 13.914] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.077 ops/ms
# Warmup Iteration   2: 8.961 ops/ms
# Warmup Iteration   3: 9.457 ops/ms
Iteration   1: 9.607 ops/ms
Iteration   2: 9.373 ops/ms
Iteration   3: 9.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.585 ±(99.9%) 3.685 ops/ms [Average]
  (min, avg, max) = (9.373, 9.585, 9.776), stdev = 0.202
  CI (99.9%): [5.900, 13.271] (assumes normal distribution)


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
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 7.715 ops/ms
# Warmup Iteration   3: 8.127 ops/ms
Iteration   1: 8.218 ops/ms
Iteration   2: 8.508 ops/ms
Iteration   3: 8.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.339 ±(99.9%) 2.745 ops/ms [Average]
  (min, avg, max) = (8.218, 8.339, 8.508), stdev = 0.150
  CI (99.9%): [5.594, 11.084] (assumes normal distribution)


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
# Warmup Iteration   1: 8.165 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.005 ms/op
Iteration   1: 3.283 ±(99.9%) 0.007 ms/op
Iteration   2: 3.196 ±(99.9%) 0.005 ms/op
Iteration   3: 3.195 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.224 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (3.195, 3.224, 3.283), stdev = 0.051
  CI (99.9%): [2.303, 4.146] (assumes normal distribution)


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
# Warmup Iteration   1: 8.565 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.003 ms/op
Iteration   1: 3.156 ±(99.9%) 0.004 ms/op
Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
Iteration   3: 3.185 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.161 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.143, 3.161, 3.185), stdev = 0.021
  CI (99.9%): [2.773, 3.549] (assumes normal distribution)


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
# Warmup Iteration   1: 8.574 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.005 ms/op
Iteration   1: 3.275 ±(99.9%) 0.005 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.242 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.200, 3.239, 3.275), stdev = 0.037
  CI (99.9%): [2.555, 3.923] (assumes normal distribution)


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
# Warmup Iteration   1: 8.904 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.005 ms/op
Iteration   1: 3.893 ±(99.9%) 0.005 ms/op
Iteration   2: 3.727 ±(99.9%) 0.012 ms/op
Iteration   3: 3.828 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.816 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (3.727, 3.816, 3.893), stdev = 0.084
  CI (99.9%): [2.291, 5.342] (assumes normal distribution)


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
# Warmup Iteration   1: 9.483 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.314 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  14.505 ms/op
                 createUser·p0.9999: 21.376 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.329 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  20.647 ms/op
                 createUser·p0.9999: 22.885 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.891 ms/op
                 createUser·p0.999:  17.603 ms/op
                 createUser·p0.9999: 24.172 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288187
  mean =      3.328 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24015 
    [ 2.500,  5.000) = 257521 
    [ 5.000,  7.500) = 5180 
    [ 7.500, 10.000) = 1033 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     17.623 ms/op
     p(99.9900) =     22.878 ms/op
     p(99.9990) =     24.588 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 9.138 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  11.786 ms/op
                 existUser·p0.9999: 23.679 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  12.670 ms/op
                 existUser·p0.9999: 22.404 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  12.979 ms/op
                 existUser·p0.9999: 23.072 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302461
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27669 
    [ 2.500,  5.000) = 268404 
    [ 5.000,  7.500) = 5129 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.762 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     23.413 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 8.203 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.010 ms/op
Iteration   1: 3.390 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   5.176 ms/op
                 getUser·p0.99:   7.994 ms/op
                 getUser·p0.999:  19.126 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 3.351 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  20.455 ms/op
                 getUser·p0.9999: 24.737 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  14.529 ms/op
                 getUser·p0.9999: 24.231 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285007
  mean =      3.365 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17080 
    [ 2.500,  5.000) = 257764 
    [ 5.000,  7.500) = 7996 
    [ 7.500, 10.000) = 1562 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     18.087 ms/op
     p(99.9900) =     25.477 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 9.229 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.013 ms/op
Iteration   1: 3.876 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  16.643 ms/op
                 listUser·p0.9999: 21.700 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 3.798 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.132 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 15.761 ms/op
                 listUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249609
  mean =      3.846 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 240835 
    [ 5.000,  7.500) = 5719 
    [ 7.500, 10.000) = 2189 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     19.981 ms/op
     p(99.9990) =     22.004 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.532 ± 4.377  ops/ms
ClientPb.existUser                       thrpt       3  10.232 ± 3.682  ops/ms
ClientPb.getUser                         thrpt       3   9.585 ± 3.685  ops/ms
ClientPb.listUser                        thrpt       3   8.339 ± 2.745  ops/ms
ClientPb.createUser                       avgt       3   3.224 ± 0.921   ms/op
ClientPb.existUser                        avgt       3   3.161 ± 0.388   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 0.684   ms/op
ClientPb.listUser                         avgt       3   3.816 ± 1.525   ms/op
ClientPb.createUser                     sample  288187   3.328 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.623           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.878           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.871           ms/op
ClientPb.existUser                      sample  302461   3.172 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.057           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.762           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.861           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.413           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.756           ms/op
ClientPb.getUser                        sample  285007   3.365 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.087           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.477           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.739           ms/op
ClientPb.listUser                       sample  249609   3.846 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.507           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.981           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.086           ms/op
