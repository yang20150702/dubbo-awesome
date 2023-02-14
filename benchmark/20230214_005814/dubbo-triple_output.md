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
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.230 ops/ms
# Warmup Iteration   3: 9.317 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 10.074 ops/ms
Iteration   3: 10.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.036 ±(99.9%) 0.999 ops/ms [Average]
  (min, avg, max) = (9.973, 10.036, 10.074), stdev = 0.055
  CI (99.9%): [9.037, 11.035] (assumes normal distribution)


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
# Warmup Iteration   1: 3.033 ops/ms
# Warmup Iteration   2: 9.178 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 10.776 ops/ms
Iteration   2: 10.140 ops/ms
Iteration   3: 10.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.549 ±(99.9%) 6.467 ops/ms [Average]
  (min, avg, max) = (10.140, 10.549, 10.776), stdev = 0.354
  CI (99.9%): [4.082, 17.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.697 ops/ms
# Warmup Iteration   2: 9.172 ops/ms
# Warmup Iteration   3: 9.832 ops/ms
Iteration   1: 9.572 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.699 ±(99.9%) 5.485 ops/ms [Average]
  (min, avg, max) = (9.482, 9.699, 10.042), stdev = 0.301
  CI (99.9%): [4.213, 15.184] (assumes normal distribution)


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
# Warmup Iteration   1: 3.288 ops/ms
# Warmup Iteration   2: 7.537 ops/ms
# Warmup Iteration   3: 8.436 ops/ms
Iteration   1: 8.275 ops/ms
Iteration   2: 7.945 ops/ms
Iteration   3: 8.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.271 ±(99.9%) 5.918 ops/ms [Average]
  (min, avg, max) = (7.945, 8.271, 8.594), stdev = 0.324
  CI (99.9%): [2.353, 14.189] (assumes normal distribution)


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
# Warmup Iteration   1: 7.780 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.005 ms/op
Iteration   1: 3.216 ±(99.9%) 0.003 ms/op
Iteration   2: 3.144 ±(99.9%) 0.006 ms/op
Iteration   3: 3.147 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.169 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.144, 3.169, 3.216), stdev = 0.041
  CI (99.9%): [2.429, 3.910] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.241 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.004 ms/op
Iteration   1: 3.231 ±(99.9%) 0.002 ms/op
Iteration   2: 3.067 ±(99.9%) 0.005 ms/op
Iteration   3: 3.199 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.166 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (3.067, 3.166, 3.231), stdev = 0.087
  CI (99.9%): [1.575, 4.757] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 6.895 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.003 ms/op
Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.129 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.080, 3.129, 3.169), stdev = 0.045
  CI (99.9%): [2.301, 3.956] (assumes normal distribution)


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
# Warmup Iteration   1: 8.973 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.004 ms/op
Iteration   1: 3.612 ±(99.9%) 0.011 ms/op
Iteration   2: 3.702 ±(99.9%) 0.004 ms/op
Iteration   3: 3.752 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.688 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (3.612, 3.688, 3.752), stdev = 0.071
  CI (99.9%): [2.395, 4.982] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  10.373 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   2: 3.331 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  16.285 ms/op
                 createUser·p0.9999: 20.329 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   3: 3.113 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  17.579 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298200
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18841 
    [ 2.500,  5.000) = 274425 
    [ 5.000,  7.500) = 4177 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     16.525 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     26.379 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.456 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 19.620 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 22.859 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 19.887 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307564
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28367 
    [ 2.500,  5.000) = 274792 
    [ 5.000,  7.500) = 3745 
    [ 7.500, 10.000) = 283 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     21.897 ms/op
     p(99.9990) =     23.273 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.865 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  17.462 ms/op
                 getUser·p0.9999: 20.244 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.473 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  8.508 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 20.278 ms/op
                 getUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305621
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8077 
    [ 2.500,  5.000) = 291135 
    [ 5.000,  7.500) = 5370 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     14.146 ms/op
     p(99.9900) =     20.658 ms/op
     p(99.9990) =     21.326 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 8.738 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.011 ms/op
Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.175 ms/op
                 listUser·p0.9999: 21.399 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 3.693 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.349 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 3.608 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   3.719 ms/op
                 listUser·p0.95:   3.932 ms/op
                 listUser·p0.99:   6.177 ms/op
                 listUser·p0.999:  14.065 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259895
  mean =      3.690 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 253166 
    [ 5.000,  7.500) = 5251 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.125 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.036 ± 0.999  ops/ms
ClientPb.existUser                       thrpt       3  10.549 ± 6.467  ops/ms
ClientPb.getUser                         thrpt       3   9.699 ± 5.485  ops/ms
ClientPb.listUser                        thrpt       3   8.271 ± 5.918  ops/ms
ClientPb.createUser                       avgt       3   3.169 ± 0.740   ms/op
ClientPb.existUser                        avgt       3   3.166 ± 1.591   ms/op
ClientPb.getUser                          avgt       3   3.129 ± 0.828   ms/op
ClientPb.listUser                         avgt       3   3.688 ± 1.294   ms/op
ClientPb.createUser                     sample  298200   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.180           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.525           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.559           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.770           ms/op
ClientPb.existUser                      sample  307564   3.119 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.754           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.977           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.897           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.626           ms/op
ClientPb.getUser                        sample  305621   3.138 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.146           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.658           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.217           ms/op
ClientPb.listUser                       sample  259895   3.690 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.349           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.479           ms/op
