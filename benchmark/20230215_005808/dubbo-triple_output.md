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
# Warmup Iteration   1: 2.349 ops/ms
# Warmup Iteration   2: 5.861 ops/ms
# Warmup Iteration   3: 9.555 ops/ms
Iteration   1: 10.111 ops/ms
Iteration   2: 9.623 ops/ms
Iteration   3: 10.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.943 ±(99.9%) 5.065 ops/ms [Average]
  (min, avg, max) = (9.623, 9.943, 10.111), stdev = 0.278
  CI (99.9%): [4.878, 15.008] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ops/ms
# Warmup Iteration   2: 9.661 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.161 ops/ms
Iteration   2: 10.180 ops/ms
Iteration   3: 9.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.106 ±(99.9%) 2.068 ops/ms [Average]
  (min, avg, max) = (9.975, 10.106, 10.180), stdev = 0.113
  CI (99.9%): [8.038, 12.173] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.122 ops/ms
# Warmup Iteration   2: 9.045 ops/ms
# Warmup Iteration   3: 9.443 ops/ms
Iteration   1: 9.492 ops/ms
Iteration   2: 10.048 ops/ms
Iteration   3: 10.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.910 ±(99.9%) 6.730 ops/ms [Average]
  (min, avg, max) = (9.492, 9.910, 10.190), stdev = 0.369
  CI (99.9%): [3.180, 16.640] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 7.412 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.411 ops/ms
Iteration   2: 8.483 ops/ms
Iteration   3: 8.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.556 ±(99.9%) 3.503 ops/ms [Average]
  (min, avg, max) = (8.411, 8.556, 8.774), stdev = 0.192
  CI (99.9%): [5.053, 12.059] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.003 ms/op
Iteration   1: 3.185 ±(99.9%) 0.003 ms/op
Iteration   2: 3.162 ±(99.9%) 0.005 ms/op
Iteration   3: 3.261 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.202 ±(99.9%) 0.942 ms/op [Average]
  (min, avg, max) = (3.162, 3.202, 3.261), stdev = 0.052
  CI (99.9%): [2.260, 4.145] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.205 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.005 ms/op
Iteration   1: 3.152 ±(99.9%) 0.006 ms/op
Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.066 ±(99.9%) 1.567 ms/op [Average]
  (min, avg, max) = (2.980, 3.066, 3.152), stdev = 0.086
  CI (99.9%): [1.499, 4.632] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.035 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.006 ms/op
Iteration   1: 3.230 ±(99.9%) 0.002 ms/op
Iteration   2: 3.188 ±(99.9%) 0.004 ms/op
Iteration   3: 3.310 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (3.188, 3.243, 3.310), stdev = 0.062
  CI (99.9%): [2.112, 4.373] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.785 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.004 ms/op
Iteration   1: 3.815 ±(99.9%) 0.007 ms/op
Iteration   2: 3.613 ±(99.9%) 0.008 ms/op
Iteration   3: 3.635 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.688 ±(99.9%) 2.023 ms/op [Average]
  (min, avg, max) = (3.613, 3.688, 3.815), stdev = 0.111
  CI (99.9%): [1.665, 5.710] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.191 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  18.560 ms/op
                 createUser·p0.9999: 21.270 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 22.676 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  17.276 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299520
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22708 
    [ 2.500,  5.000) = 271971 
    [ 5.000,  7.500) = 3959 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 187 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     21.964 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 7.921 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.279 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  9.788 ms/op
                 existUser·p0.9999: 24.936 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   4.783 ms/op
                 existUser·p0.999:  15.942 ms/op
                 existUser·p0.9999: 23.971 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  8.976 ms/op
                 existUser·p0.9999: 24.314 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301457
  mean =      3.183 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22742 
    [ 2.500,  5.000) = 273047 
    [ 5.000,  7.500) = 4687 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     12.190 ms/op
     p(99.9900) =     24.506 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.242 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.457 ms/op
                 getUser·p0.999:  14.843 ms/op
                 getUser·p0.9999: 19.141 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  20.227 ms/op
                 getUser·p0.9999: 22.562 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 24.583 ms/op
                 getUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288877
  mean =      3.321 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13151 
    [ 2.500,  5.000) = 266642 
    [ 5.000,  7.500) = 7864 
    [ 7.500, 10.000) = 736 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     13.705 ms/op
     p(99.9900) =     23.174 ms/op
     p(99.9990) =     26.218 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.012 ms/op
Iteration   1: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  16.004 ms/op
                 listUser·p0.9999: 35.127 ms/op
                 listUser·p1.00:   36.176 ms/op

Iteration   2: 3.843 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.852 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 16.400 ms/op
                 listUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247208
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 237523 
    [ 5.000,  7.500) = 7397 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     14.611 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     35.886 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.943 ± 5.065  ops/ms
ClientPb.existUser                       thrpt       3  10.106 ± 2.068  ops/ms
ClientPb.getUser                         thrpt       3   9.910 ± 6.730  ops/ms
ClientPb.listUser                        thrpt       3   8.556 ± 3.503  ops/ms
ClientPb.createUser                       avgt       3   3.202 ± 0.942   ms/op
ClientPb.existUser                        avgt       3   3.066 ± 1.567   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 1.131   ms/op
ClientPb.listUser                         avgt       3   3.688 ± 2.023   ms/op
ClientPb.createUser                     sample  299520   3.203 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.206           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.317           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.964           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.970           ms/op
ClientPb.existUser                      sample  301457   3.183 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.952           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.506           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  288877   3.321 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.104           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.705           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.174           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.477           ms/op
ClientPb.listUser                       sample  247208   3.882 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.611           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.489           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.176           ms/op
