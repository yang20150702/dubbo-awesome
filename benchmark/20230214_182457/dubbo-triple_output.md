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
# Warmup Iteration   1: 2.501 ops/ms
# Warmup Iteration   2: 5.459 ops/ms
# Warmup Iteration   3: 9.033 ops/ms
Iteration   1: 9.600 ops/ms
Iteration   2: 9.942 ops/ms
Iteration   3: 10.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.882 ±(99.9%) 4.696 ops/ms [Average]
  (min, avg, max) = (9.600, 9.882, 10.105), stdev = 0.257
  CI (99.9%): [5.186, 14.579] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.524 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 10.586 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.431 ±(99.9%) 5.183 ops/ms [Average]
  (min, avg, max) = (10.103, 10.431, 10.604), stdev = 0.284
  CI (99.9%): [5.248, 15.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.425 ops/ms
# Warmup Iteration   2: 8.838 ops/ms
# Warmup Iteration   3: 9.717 ops/ms
Iteration   1: 9.984 ops/ms
Iteration   2: 9.730 ops/ms
Iteration   3: 10.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.920 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (9.730, 9.920, 10.046), stdev = 0.168
  CI (99.9%): [6.862, 12.978] (assumes normal distribution)


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
# Warmup Iteration   1: 3.138 ops/ms
# Warmup Iteration   2: 7.595 ops/ms
# Warmup Iteration   3: 8.187 ops/ms
Iteration   1: 8.507 ops/ms
Iteration   2: 8.630 ops/ms
Iteration   3: 8.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.620 ±(99.9%) 1.969 ops/ms [Average]
  (min, avg, max) = (8.507, 8.620, 8.723), stdev = 0.108
  CI (99.9%): [6.650, 10.589] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.748 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
Iteration   3: 3.275 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.146, 3.205, 3.275), stdev = 0.066
  CI (99.9%): [2.010, 4.401] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.910 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.002 ms/op
Iteration   1: 3.075 ±(99.9%) 0.004 ms/op
Iteration   2: 3.191 ±(99.9%) 0.007 ms/op
Iteration   3: 3.115 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.127 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.075, 3.127, 3.191), stdev = 0.059
  CI (99.9%): [2.046, 4.208] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.999 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.002 ms/op
Iteration   1: 3.251 ±(99.9%) 0.003 ms/op
Iteration   2: 3.281 ±(99.9%) 0.006 ms/op
Iteration   3: 3.269 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.267 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (3.251, 3.267, 3.281), stdev = 0.015
  CI (99.9%): [2.984, 3.549] (assumes normal distribution)


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
# Warmup Iteration   1: 9.441 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.004 ms/op
Iteration   1: 3.811 ±(99.9%) 0.005 ms/op
Iteration   2: 3.828 ±(99.9%) 0.008 ms/op
Iteration   3: 3.731 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.790 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (3.731, 3.790, 3.828), stdev = 0.052
  CI (99.9%): [2.846, 4.734] (assumes normal distribution)


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
# Warmup Iteration   1: 8.169 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
Iteration   1: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  13.500 ms/op
                 createUser·p0.9999: 28.161 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 3.214 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.247 ms/op
                 createUser·p0.999:  10.412 ms/op
                 createUser·p0.9999: 25.233 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.273 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  17.661 ms/op
                 createUser·p0.9999: 27.142 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298052
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16686 
    [ 2.500,  5.000) = 276351 
    [ 5.000,  7.500) = 3979 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.273 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     17.162 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     28.608 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 7.808 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 21.536 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 23.046 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  14.205 ms/op
                 existUser·p0.9999: 19.981 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310550
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17135 
    [ 2.500,  5.000) = 289453 
    [ 5.000,  7.500) = 3461 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     14.032 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     23.619 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 8.263 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.432 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  11.581 ms/op
                 getUser·p0.9999: 17.898 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.305 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 21.910 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  10.121 ms/op
                 getUser·p0.9999: 19.347 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300245
  mean =      3.194 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13580 
    [ 2.500,  5.000) = 280366 
    [ 5.000,  7.500) = 5676 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     15.852 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 9.629 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.012 ms/op
Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  20.137 ms/op
                 listUser·p0.9999: 28.562 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   2: 3.960 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  13.947 ms/op
                 listUser·p0.9999: 18.839 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245156
  mean =      3.913 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 235602 
    [ 5.000,  7.500) = 7312 
    [ 7.500, 10.000) = 1509 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     14.907 ms/op
     p(99.9900) =     26.230 ms/op
     p(99.9990) =     29.016 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.882 ± 4.696  ops/ms
ClientPb.existUser                       thrpt       3  10.431 ± 5.183  ops/ms
ClientPb.getUser                         thrpt       3   9.920 ± 3.058  ops/ms
ClientPb.listUser                        thrpt       3   8.620 ± 1.969  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 1.196   ms/op
ClientPb.existUser                        avgt       3   3.127 ± 1.081   ms/op
ClientPb.getUser                          avgt       3   3.267 ± 0.282   ms/op
ClientPb.listUser                         avgt       3   3.790 ± 0.944   ms/op
ClientPb.createUser                     sample  298052   3.222 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.273           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.162           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.230           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.770           ms/op
ClientPb.existUser                      sample  310550   3.091 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.094           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.032           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.724           ms/op
ClientPb.getUser                        sample  300245   3.194 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.315           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.852           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.382           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.938           ms/op
ClientPb.listUser                       sample  245156   3.913 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.871           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.907           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.230           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.262           ms/op
