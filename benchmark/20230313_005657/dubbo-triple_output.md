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
# Warmup Iteration   1: 2.566 ops/ms
# Warmup Iteration   2: 5.668 ops/ms
# Warmup Iteration   3: 9.094 ops/ms
Iteration   1: 9.507 ops/ms
Iteration   2: 9.992 ops/ms
Iteration   3: 10.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.898 ±(99.9%) 6.454 ops/ms [Average]
  (min, avg, max) = (9.507, 9.898, 10.196), stdev = 0.354
  CI (99.9%): [3.444, 16.352] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.833 ops/ms
# Warmup Iteration   2: 9.375 ops/ms
# Warmup Iteration   3: 10.434 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.105 ops/ms
Iteration   3: 10.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.324 ±(99.9%) 3.616 ops/ms [Average]
  (min, avg, max) = (10.105, 10.324, 10.491), stdev = 0.198
  CI (99.9%): [6.708, 13.940] (assumes normal distribution)


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
# Warmup Iteration   1: 3.595 ops/ms
# Warmup Iteration   2: 8.996 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 10.028 ops/ms
Iteration   2: 9.995 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.107 ±(99.9%) 3.029 ops/ms [Average]
  (min, avg, max) = (9.995, 10.107, 10.298), stdev = 0.166
  CI (99.9%): [7.078, 13.135] (assumes normal distribution)


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
# Warmup Iteration   1: 3.303 ops/ms
# Warmup Iteration   2: 7.726 ops/ms
# Warmup Iteration   3: 8.654 ops/ms
Iteration   1: 8.489 ops/ms
Iteration   2: 8.281 ops/ms
Iteration   3: 8.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.420 ±(99.9%) 2.195 ops/ms [Average]
  (min, avg, max) = (8.281, 8.420, 8.491), stdev = 0.120
  CI (99.9%): [6.225, 10.615] (assumes normal distribution)


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
# Warmup Iteration   1: 8.427 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.008 ms/op
Iteration   1: 3.219 ±(99.9%) 0.011 ms/op
Iteration   2: 3.239 ±(99.9%) 0.002 ms/op
Iteration   3: 3.235 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.231 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.219, 3.231, 3.239), stdev = 0.011
  CI (99.9%): [3.039, 3.423] (assumes normal distribution)


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
# Warmup Iteration   1: 6.561 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.004 ms/op
Iteration   1: 3.055 ±(99.9%) 0.004 ms/op
Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
Iteration   3: 3.239 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.151 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (3.055, 3.151, 3.239), stdev = 0.092
  CI (99.9%): [1.471, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 7.986 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.002 ms/op
Iteration   1: 3.160 ±(99.9%) 0.003 ms/op
Iteration   2: 3.168 ±(99.9%) 0.004 ms/op
Iteration   3: 3.088 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.139 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.088, 3.139, 3.168), stdev = 0.044
  CI (99.9%): [2.327, 3.950] (assumes normal distribution)


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
# Warmup Iteration   1: 9.466 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.003 ms/op
Iteration   1: 3.740 ±(99.9%) 0.006 ms/op
Iteration   2: 3.709 ±(99.9%) 0.010 ms/op
Iteration   3: 3.838 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.762 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (3.709, 3.762, 3.838), stdev = 0.067
  CI (99.9%): [2.535, 4.989] (assumes normal distribution)


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
# Warmup Iteration   1: 9.202 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
Iteration   1: 3.223 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.970 ms/op
                 createUser·p0.999:  20.462 ms/op
                 createUser·p0.9999: 26.577 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 25.083 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.354 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  17.520 ms/op
                 createUser·p0.9999: 21.297 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296314
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19267 
    [ 2.500,  5.000) = 270351 
    [ 5.000,  7.500) = 5640 
    [ 7.500, 10.000) = 552 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     25.706 ms/op
     p(99.9990) =     26.741 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 7.944 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.008 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 19.697 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  8.969 ms/op
                 existUser·p0.9999: 22.512 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 22.104 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309067
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18933 
    [ 2.500,  5.000) = 284448 
    [ 5.000,  7.500) = 4908 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.869 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 7.556 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.010 ms/op
Iteration   1: 3.319 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  16.013 ms/op
                 getUser·p0.9999: 25.133 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  9.585 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  14.583 ms/op
                 getUser·p0.9999: 22.715 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295485
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14804 
    [ 2.500,  5.000) = 272885 
    [ 5.000,  7.500) = 7111 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.883 ms/op
     p(99.9000) =     13.198 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     25.274 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 10.113 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.011 ms/op
Iteration   1: 3.779 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  16.888 ms/op
                 listUser·p0.9999: 20.351 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 3.714 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  12.993 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.833 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 16.105 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254134
  mean =      3.775 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 121 
    [ 2.500,  5.000) = 245788 
    [ 5.000,  7.500) = 6234 
    [ 7.500, 10.000) = 1229 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     20.772 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.898 ± 6.454  ops/ms
ClientPb.existUser                       thrpt       3  10.324 ± 3.616  ops/ms
ClientPb.getUser                         thrpt       3  10.107 ± 3.029  ops/ms
ClientPb.listUser                        thrpt       3   8.420 ± 2.195  ops/ms
ClientPb.createUser                       avgt       3   3.231 ± 0.192   ms/op
ClientPb.existUser                        avgt       3   3.151 ± 1.680   ms/op
ClientPb.getUser                          avgt       3   3.139 ± 0.811   ms/op
ClientPb.listUser                         avgt       3   3.762 ± 1.227   ms/op
ClientPb.createUser                     sample  296314   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.350           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.706           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.903           ms/op
ClientPb.existUser                      sample  309067   3.106 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.998           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.011           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.053           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.331           ms/op
ClientPb.getUser                        sample  295485   3.246 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.112           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.883           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.198           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.001           ms/op
ClientPb.listUser                       sample  254134   3.775 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.372           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.399           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.873           ms/op
