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
# Warmup Iteration   1: 2.432 ops/ms
# Warmup Iteration   2: 6.270 ops/ms
# Warmup Iteration   3: 9.023 ops/ms
Iteration   1: 9.764 ops/ms
Iteration   2: 9.872 ops/ms
Iteration   3: 9.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.828 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (9.764, 9.828, 9.872), stdev = 0.057
  CI (99.9%): [8.789, 10.867] (assumes normal distribution)


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
# Warmup Iteration   1: 3.966 ops/ms
# Warmup Iteration   2: 9.918 ops/ms
# Warmup Iteration   3: 10.068 ops/ms
Iteration   1: 10.428 ops/ms
Iteration   2: 10.676 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.421 ±(99.9%) 4.712 ops/ms [Average]
  (min, avg, max) = (10.160, 10.421, 10.676), stdev = 0.258
  CI (99.9%): [5.709, 15.134] (assumes normal distribution)


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
# Warmup Iteration   1: 3.431 ops/ms
# Warmup Iteration   2: 8.641 ops/ms
# Warmup Iteration   3: 9.715 ops/ms
Iteration   1: 9.533 ops/ms
Iteration   2: 9.691 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.666 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (9.533, 9.666, 9.774), stdev = 0.122
  CI (99.9%): [7.433, 11.899] (assumes normal distribution)


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
# Warmup Iteration   1: 3.433 ops/ms
# Warmup Iteration   2: 7.713 ops/ms
# Warmup Iteration   3: 8.517 ops/ms
Iteration   1: 8.691 ops/ms
Iteration   2: 8.563 ops/ms
Iteration   3: 8.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.661 ±(99.9%) 1.600 ops/ms [Average]
  (min, avg, max) = (8.563, 8.661, 8.731), stdev = 0.088
  CI (99.9%): [7.061, 10.262] (assumes normal distribution)


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
# Warmup Iteration   1: 8.503 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.008 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
Iteration   3: 3.093 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.133 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (3.093, 3.133, 3.175), stdev = 0.041
  CI (99.9%): [2.386, 3.880] (assumes normal distribution)


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
# Warmup Iteration   1: 8.182 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
Iteration   3: 3.044 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.054 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (3.041, 3.054, 3.076), stdev = 0.019
  CI (99.9%): [2.701, 3.406] (assumes normal distribution)


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
# Warmup Iteration   1: 7.887 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.004 ms/op
Iteration   1: 3.237 ±(99.9%) 0.003 ms/op
Iteration   2: 3.245 ±(99.9%) 0.004 ms/op
Iteration   3: 3.169 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.217 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.169, 3.217, 3.245), stdev = 0.042
  CI (99.9%): [2.450, 3.984] (assumes normal distribution)


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
# Warmup Iteration   1: 9.161 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.007 ms/op
Iteration   1: 3.773 ±(99.9%) 0.006 ms/op
Iteration   2: 3.650 ±(99.9%) 0.011 ms/op
Iteration   3: 3.671 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.698 ±(99.9%) 1.199 ms/op [Average]
  (min, avg, max) = (3.650, 3.698, 3.773), stdev = 0.066
  CI (99.9%): [2.499, 4.898] (assumes normal distribution)


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
# Warmup Iteration   1: 7.910 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
Iteration   1: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 21.435 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 3.206 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 22.119 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  14.320 ms/op
                 createUser·p0.9999: 24.217 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297744
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22637 
    [ 2.500,  5.000) = 269919 
    [ 5.000,  7.500) = 4248 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     22.453 ms/op
     p(99.9990) =     24.937 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.504 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.151 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.755 ms/op
                 existUser·p0.9999: 19.590 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  15.057 ms/op
                 existUser·p0.9999: 21.192 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 21.667 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306294
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19674 
    [ 2.500,  5.000) = 281649 
    [ 5.000,  7.500) = 4067 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     14.806 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.243 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 8.096 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.941 ms/op
                 getUser·p0.999:  10.116 ms/op
                 getUser·p0.9999: 18.387 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.889 ms/op
                 getUser·p0.999:  15.403 ms/op
                 getUser·p0.9999: 21.010 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  14.628 ms/op
                 getUser·p0.9999: 19.300 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296914
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14365 
    [ 2.500,  5.000) = 275434 
    [ 5.000,  7.500) = 6087 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     14.399 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     21.697 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 8.645 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.012 ms/op
Iteration   1: 3.749 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 18.103 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.739 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.795 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255252
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 246830 
    [ 5.000,  7.500) = 6186 
    [ 7.500, 10.000) = 1384 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     22.264 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.828 ± 1.039  ops/ms
ClientPb.existUser                       thrpt       3  10.421 ± 4.712  ops/ms
ClientPb.getUser                         thrpt       3   9.666 ± 2.233  ops/ms
ClientPb.listUser                        thrpt       3   8.661 ± 1.600  ops/ms
ClientPb.createUser                       avgt       3   3.133 ± 0.747   ms/op
ClientPb.existUser                        avgt       3   3.054 ± 0.352   ms/op
ClientPb.getUser                          avgt       3   3.217 ± 0.767   ms/op
ClientPb.listUser                         avgt       3   3.698 ± 1.199   ms/op
ClientPb.createUser                     sample  297744   3.221 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.006           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.453           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.002           ms/op
ClientPb.existUser                      sample  306294   3.132 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.098           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.806           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.070           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.381           ms/op
ClientPb.getUser                        sample  296914   3.230 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.399           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.546           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.922           ms/op
ClientPb.listUser                       sample  255252   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.485           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.266           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
