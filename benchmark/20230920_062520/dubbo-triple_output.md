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
# Warmup Iteration   1: 2.364 ops/ms
# Warmup Iteration   2: 6.123 ops/ms
# Warmup Iteration   3: 8.916 ops/ms
Iteration   1: 9.798 ops/ms
Iteration   2: 9.936 ops/ms
Iteration   3: 9.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.857 ±(99.9%) 1.300 ops/ms [Average]
  (min, avg, max) = (9.798, 9.857, 9.936), stdev = 0.071
  CI (99.9%): [8.557, 11.157] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.458 ops/ms
# Warmup Iteration   2: 9.186 ops/ms
# Warmup Iteration   3: 10.090 ops/ms
Iteration   1: 10.144 ops/ms
Iteration   2: 10.160 ops/ms
Iteration   3: 10.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.184 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (10.144, 10.184, 10.248), stdev = 0.056
  CI (99.9%): [9.163, 11.206] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.555 ops/ms
# Warmup Iteration   2: 9.149 ops/ms
# Warmup Iteration   3: 9.716 ops/ms
Iteration   1: 9.834 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.881 ±(99.9%) 2.605 ops/ms [Average]
  (min, avg, max) = (9.769, 9.881, 10.042), stdev = 0.143
  CI (99.9%): [7.276, 12.487] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.150 ops/ms
# Warmup Iteration   2: 7.650 ops/ms
# Warmup Iteration   3: 8.251 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 8.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.314 ±(99.9%) 2.084 ops/ms [Average]
  (min, avg, max) = (8.246, 8.314, 8.446), stdev = 0.114
  CI (99.9%): [6.230, 10.399] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.323 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.002 ms/op
Iteration   1: 3.303 ±(99.9%) 0.003 ms/op
Iteration   2: 3.267 ±(99.9%) 0.003 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.262 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (3.217, 3.262, 3.303), stdev = 0.043
  CI (99.9%): [2.473, 4.052] (assumes normal distribution)


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
# Warmup Iteration   1: 7.465 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.003 ms/op
Iteration   1: 3.165 ±(99.9%) 0.004 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.175 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.162 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.146, 3.162, 3.175), stdev = 0.015
  CI (99.9%): [2.888, 3.436] (assumes normal distribution)


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
# Warmup Iteration   1: 8.054 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.004 ms/op
Iteration   1: 3.224 ±(99.9%) 0.002 ms/op
Iteration   2: 3.230 ±(99.9%) 0.004 ms/op
Iteration   3: 3.216 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.216, 3.223, 3.230), stdev = 0.007
  CI (99.9%): [3.094, 3.352] (assumes normal distribution)


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
# Warmup Iteration   1: 8.687 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.004 ms/op
Iteration   1: 3.826 ±(99.9%) 0.006 ms/op
Iteration   2: 3.757 ±(99.9%) 0.006 ms/op
Iteration   3: 3.864 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.816 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.757, 3.816, 3.864), stdev = 0.055
  CI (99.9%): [2.820, 4.811] (assumes normal distribution)


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
# Warmup Iteration   1: 8.051 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
Iteration   1: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  13.426 ms/op
                 createUser·p0.9999: 20.298 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.391 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  14.238 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.990 ms/op
                 createUser·p0.999:  18.786 ms/op
                 createUser·p0.9999: 21.205 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297239
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15417 
    [ 2.500,  5.000) = 277764 
    [ 5.000,  7.500) = 3292 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     18.015 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.955 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 8.230 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
Iteration   1: 3.205 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  9.117 ms/op
                 existUser·p0.9999: 18.909 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.523 ms/op
                 existUser·p0.999:  15.563 ms/op
                 existUser·p0.9999: 20.246 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  14.944 ms/op
                 existUser·p0.9999: 19.700 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299017
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11664 
    [ 2.500,  5.000) = 281738 
    [ 5.000,  7.500) = 4623 
    [ 7.500, 10.000) = 390 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     21.039 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 7.331 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.010 ms/op
Iteration   1: 3.395 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  18.261 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  12.822 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.262 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   6.129 ms/op
                 getUser·p0.999:  15.023 ms/op
                 getUser·p0.9999: 22.354 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292663
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7172 
    [ 2.500,  5.000) = 278762 
    [ 5.000,  7.500) = 5776 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     15.467 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     23.172 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 8.653 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.012 ms/op
Iteration   1: 3.888 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 19.711 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 3.921 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 14.514 ms/op
                 listUser·p1.00:   15.122 ms/op

Iteration   3: 3.818 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 14.426 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247588
  mean =      3.875 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 240223 
    [ 5.000,  7.500) = 5585 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 375 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     13.278 ms/op
     p(99.9900) =     18.784 ms/op
     p(99.9990) =     20.958 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.857 ± 1.300  ops/ms
ClientPb.existUser                       thrpt       3  10.184 ± 1.022  ops/ms
ClientPb.getUser                         thrpt       3   9.881 ± 2.605  ops/ms
ClientPb.listUser                        thrpt       3   8.314 ± 2.084  ops/ms
ClientPb.createUser                       avgt       3   3.262 ± 0.790   ms/op
ClientPb.existUser                        avgt       3   3.162 ± 0.274   ms/op
ClientPb.getUser                          avgt       3   3.223 ± 0.129   ms/op
ClientPb.listUser                         avgt       3   3.816 ± 0.996   ms/op
ClientPb.createUser                     sample  297239   3.227 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.775           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.015           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.217           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.508           ms/op
ClientPb.existUser                      sample  299017   3.208 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.157           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.792           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.299           ms/op
ClientPb.getUser                        sample  292663   3.279 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.467           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.888           ms/op
ClientPb.listUser                       sample  247588   3.875 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.278           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.784           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.529           ms/op
