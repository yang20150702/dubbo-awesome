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
# Warmup Iteration   1: 2.472 ops/ms
# Warmup Iteration   2: 6.724 ops/ms
# Warmup Iteration   3: 9.152 ops/ms
Iteration   1: 9.887 ops/ms
Iteration   2: 9.962 ops/ms
Iteration   3: 10.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.011 ±(99.9%) 2.832 ops/ms [Average]
  (min, avg, max) = (9.887, 10.011, 10.185), stdev = 0.155
  CI (99.9%): [7.180, 12.843] (assumes normal distribution)


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
# Warmup Iteration   1: 3.164 ops/ms
# Warmup Iteration   2: 8.935 ops/ms
# Warmup Iteration   3: 10.147 ops/ms
Iteration   1: 10.365 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.413 ±(99.9%) 3.445 ops/ms [Average]
  (min, avg, max) = (10.253, 10.413, 10.621), stdev = 0.189
  CI (99.9%): [6.968, 13.858] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ops/ms
# Warmup Iteration   2: 9.157 ops/ms
# Warmup Iteration   3: 9.519 ops/ms
Iteration   1: 9.898 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.064 ±(99.9%) 3.535 ops/ms [Average]
  (min, avg, max) = (9.898, 10.064, 10.277), stdev = 0.194
  CI (99.9%): [6.529, 13.599] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 7.823 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.499 ops/ms
Iteration   2: 8.555 ops/ms
Iteration   3: 8.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.566 ±(99.9%) 1.344 ops/ms [Average]
  (min, avg, max) = (8.499, 8.566, 8.645), stdev = 0.074
  CI (99.9%): [7.223, 9.910] (assumes normal distribution)


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
# Warmup Iteration   1: 8.324 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.003 ms/op
Iteration   1: 3.246 ±(99.9%) 0.006 ms/op
Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
Iteration   3: 3.149 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.149, 3.195, 3.246), stdev = 0.049
  CI (99.9%): [2.308, 4.082] (assumes normal distribution)


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
# Warmup Iteration   1: 6.103 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.047 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (2.998, 3.047, 3.091), stdev = 0.046
  CI (99.9%): [2.199, 3.895] (assumes normal distribution)


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
# Warmup Iteration   1: 8.089 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.003 ms/op
Iteration   1: 3.115 ±(99.9%) 0.005 ms/op
Iteration   2: 3.190 ±(99.9%) 0.003 ms/op
Iteration   3: 3.096 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.134 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.096, 3.134, 3.190), stdev = 0.050
  CI (99.9%): [2.219, 4.048] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.268 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.011 ms/op
Iteration   1: 3.723 ±(99.9%) 0.007 ms/op
Iteration   2: 3.781 ±(99.9%) 0.010 ms/op
Iteration   3: 3.739 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.748 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (3.723, 3.748, 3.781), stdev = 0.030
  CI (99.9%): [3.201, 4.295] (assumes normal distribution)


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
# Warmup Iteration   1: 8.318 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
Iteration   1: 3.121 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  18.009 ms/op
                 createUser·p0.9999: 21.062 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.202 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  18.162 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  16.891 ms/op
                 createUser·p0.9999: 19.300 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297762
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20387 
    [ 2.500,  5.000) = 269316 
    [ 5.000,  7.500) = 7033 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 222 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     22.519 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 7.788 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
Iteration   1: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 20.320 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  12.406 ms/op
                 existUser·p0.9999: 20.304 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 317404
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22424 
    [ 2.500,  5.000) = 291271 
    [ 5.000,  7.500) = 3067 
    [ 7.500, 10.000) = 267 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.183 ms/op
     p(95.0000) =      3.355 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     12.170 ms/op
     p(99.9900) =     23.503 ms/op
     p(99.9990) =     25.577 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 8.475 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.249 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  17.023 ms/op
                 getUser·p0.9999: 27.001 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  15.105 ms/op
                 getUser·p0.9999: 20.754 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  15.466 ms/op
                 getUser·p0.9999: 17.614 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297954
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20519 
    [ 2.500,  5.000) = 269335 
    [ 5.000,  7.500) = 6991 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     16.303 ms/op
     p(99.9900) =     26.024 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 9.058 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.011 ms/op
Iteration   1: 3.728 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   2: 3.711 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.399 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   3: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.289 ms/op
                 listUser·p0.999:  13.797 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256808
  mean =      3.734 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 248774 
    [ 5.000,  7.500) = 6140 
    [ 7.500, 10.000) = 1182 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     19.634 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.011 ± 2.832  ops/ms
ClientPb.existUser                       thrpt       3  10.413 ± 3.445  ops/ms
ClientPb.getUser                         thrpt       3  10.064 ± 3.535  ops/ms
ClientPb.listUser                        thrpt       3   8.566 ± 1.344  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 0.887   ms/op
ClientPb.existUser                        avgt       3   3.047 ± 0.848   ms/op
ClientPb.getUser                          avgt       3   3.134 ± 0.914   ms/op
ClientPb.listUser                         avgt       3   3.748 ± 0.547   ms/op
ClientPb.createUser                     sample  297762   3.219 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.519           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.543           ms/op
ClientPb.existUser                      sample  317404   3.023 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.170           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.503           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.083           ms/op
ClientPb.getUser                        sample  297954   3.221 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.143           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.303           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.024           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.066           ms/op
ClientPb.listUser                       sample  256808   3.734 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.339           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.400           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.218           ms/op
