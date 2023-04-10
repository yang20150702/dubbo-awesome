# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.725 ops/ms
# Warmup Iteration   2: 6.016 ops/ms
# Warmup Iteration   3: 9.432 ops/ms
Iteration   1: 9.849 ops/ms
Iteration   2: 9.904 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.849 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (9.793, 9.849, 9.904), stdev = 0.056
  CI (99.9%): [8.828, 10.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.326 ops/ms
# Warmup Iteration   2: 9.130 ops/ms
# Warmup Iteration   3: 9.747 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.102 ops/ms
Iteration   3: 10.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.244 ±(99.9%) 3.724 ops/ms [Average]
  (min, avg, max) = (10.102, 10.244, 10.478), stdev = 0.204
  CI (99.9%): [6.520, 13.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.549 ops/ms
# Warmup Iteration   2: 9.475 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.144 ±(99.9%) 2.181 ops/ms [Average]
  (min, avg, max) = (10.015, 10.144, 10.250), stdev = 0.120
  CI (99.9%): [7.964, 12.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.512 ops/ms
# Warmup Iteration   2: 8.058 ops/ms
# Warmup Iteration   3: 8.581 ops/ms
Iteration   1: 8.572 ops/ms
Iteration   2: 8.672 ops/ms
Iteration   3: 8.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.621 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (8.572, 8.621, 8.672), stdev = 0.050
  CI (99.9%): [7.706, 9.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.245 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.002 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
Iteration   3: 3.180 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.160 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (3.089, 3.160, 3.210), stdev = 0.063
  CI (99.9%): [2.015, 4.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.229 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.004 ms/op
Iteration   1: 3.149 ±(99.9%) 0.006 ms/op
Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
Iteration   3: 3.088 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.075 ±(99.9%) 1.469 ms/op [Average]
  (min, avg, max) = (2.989, 3.075, 3.149), stdev = 0.081
  CI (99.9%): [1.606, 4.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.065 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.002 ms/op
Iteration   1: 3.126 ±(99.9%) 0.001 ms/op
Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
Iteration   3: 3.192 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.125 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (3.059, 3.125, 3.192), stdev = 0.066
  CI (99.9%): [1.916, 4.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.079 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.006 ms/op
Iteration   1: 3.590 ±(99.9%) 0.010 ms/op
Iteration   2: 3.641 ±(99.9%) 0.009 ms/op
Iteration   3: 3.631 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.620 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.590, 3.620, 3.641), stdev = 0.027
  CI (99.9%): [3.126, 4.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.035 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.009 ms/op
Iteration   1: 3.306 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  13.908 ms/op
                 createUser·p0.9999: 20.753 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  10.945 ms/op
                 createUser·p0.9999: 25.031 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.114 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  16.371 ms/op
                 createUser·p0.9999: 27.844 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300798
  mean =      3.191 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31465 
    [ 2.500,  5.000) = 264097 
    [ 5.000,  7.500) = 4366 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.930 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  8.094 ms/op
                 existUser·p0.9999: 19.474 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 33.522 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  10.275 ms/op
                 existUser·p0.9999: 21.087 ms/op
                 existUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313145
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30728 
    [ 2.500,  5.000) = 279077 
    [ 5.000,  7.500) = 2802 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     32.261 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.296 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.010 ms/op
Iteration   1: 3.175 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  17.826 ms/op
                 getUser·p0.9999: 20.346 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  9.276 ms/op
                 getUser·p0.9999: 22.675 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  13.251 ms/op
                 getUser·p0.9999: 21.629 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297489
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18843 
    [ 2.500,  5.000) = 271548 
    [ 5.000,  7.500) = 6342 
    [ 7.500, 10.000) = 384 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     21.996 ms/op
     p(99.9990) =     23.106 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.908 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.011 ms/op
Iteration   1: 3.667 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.535 ms/op
                 listUser·p0.999:  14.838 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 3.777 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 16.318 ms/op
                 listUser·p1.00:   16.335 ms/op

Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  12.973 ms/op
                 listUser·p0.9999: 14.953 ms/op
                 listUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255478
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 246181 
    [ 5.000,  7.500) = 7190 
    [ 7.500, 10.000) = 1326 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     23.116 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.849 ± 1.021  ops/ms
ClientPb.existUser                       thrpt       3  10.244 ± 3.724  ops/ms
ClientPb.getUser                         thrpt       3  10.144 ± 2.181  ops/ms
ClientPb.listUser                        thrpt       3   8.621 ± 0.915  ops/ms
ClientPb.createUser                       avgt       3   3.160 ± 1.145   ms/op
ClientPb.existUser                        avgt       3   3.075 ± 1.469   ms/op
ClientPb.getUser                          avgt       3   3.125 ± 1.209   ms/op
ClientPb.listUser                         avgt       3   3.620 ± 0.495   ms/op
ClientPb.createUser                     sample  300798   3.191 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.977           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.860           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.230           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.180           ms/op
ClientPb.existUser                      sample  313145   3.064 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.013           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.239           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.261           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  297489   3.226 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.067           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.828           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.996           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.626           ms/op
ClientPb.listUser                       sample  255478   3.757 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.479           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.116           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
