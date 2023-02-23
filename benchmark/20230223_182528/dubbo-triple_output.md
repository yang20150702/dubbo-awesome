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
# Warmup Iteration   1: 2.308 ops/ms
# Warmup Iteration   2: 5.521 ops/ms
# Warmup Iteration   3: 9.530 ops/ms
Iteration   1: 9.663 ops/ms
Iteration   2: 10.140 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.978 ±(99.9%) 4.989 ops/ms [Average]
  (min, avg, max) = (9.663, 9.978, 10.140), stdev = 0.273
  CI (99.9%): [4.989, 14.967] (assumes normal distribution)


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
# Warmup Iteration   1: 3.214 ops/ms
# Warmup Iteration   2: 9.203 ops/ms
# Warmup Iteration   3: 9.909 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 10.162 ops/ms
Iteration   3: 10.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.369 ±(99.9%) 7.271 ops/ms [Average]
  (min, avg, max) = (10.117, 10.369, 10.828), stdev = 0.399
  CI (99.9%): [3.098, 17.640] (assumes normal distribution)


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
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 8.913 ops/ms
# Warmup Iteration   3: 9.671 ops/ms
Iteration   1: 9.771 ops/ms
Iteration   2: 9.962 ops/ms
Iteration   3: 10.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.999 ±(99.9%) 4.542 ops/ms [Average]
  (min, avg, max) = (9.771, 9.999, 10.264), stdev = 0.249
  CI (99.9%): [5.458, 14.541] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.455 ops/ms
# Warmup Iteration   2: 7.872 ops/ms
# Warmup Iteration   3: 8.362 ops/ms
Iteration   1: 8.665 ops/ms
Iteration   2: 8.657 ops/ms
Iteration   3: 8.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.683 ±(99.9%) 0.690 ops/ms [Average]
  (min, avg, max) = (8.657, 8.683, 8.726), stdev = 0.038
  CI (99.9%): [7.992, 9.373] (assumes normal distribution)


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
# Warmup Iteration   1: 9.328 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.308 ±(99.9%) 0.004 ms/op
Iteration   2: 3.249 ±(99.9%) 0.006 ms/op
Iteration   3: 3.065 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.208 ±(99.9%) 2.314 ms/op [Average]
  (min, avg, max) = (3.065, 3.208, 3.308), stdev = 0.127
  CI (99.9%): [0.894, 5.521] (assumes normal distribution)


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
# Warmup Iteration   1: 7.461 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op
Iteration   2: 2.954 ±(99.9%) 0.004 ms/op
Iteration   3: 3.051 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.056 ±(99.9%) 1.899 ms/op [Average]
  (min, avg, max) = (2.954, 3.056, 3.162), stdev = 0.104
  CI (99.9%): [1.157, 4.955] (assumes normal distribution)


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
# Warmup Iteration   1: 8.101 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.004 ms/op
Iteration   1: 3.194 ±(99.9%) 0.003 ms/op
Iteration   2: 3.276 ±(99.9%) 0.003 ms/op
Iteration   3: 3.134 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.201 ±(99.9%) 1.301 ms/op [Average]
  (min, avg, max) = (3.134, 3.201, 3.276), stdev = 0.071
  CI (99.9%): [1.900, 4.502] (assumes normal distribution)


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
# Warmup Iteration   1: 8.940 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.003 ms/op
Iteration   1: 3.743 ±(99.9%) 0.006 ms/op
Iteration   2: 3.752 ±(99.9%) 0.007 ms/op
Iteration   3: 3.691 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.729 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.691, 3.729, 3.752), stdev = 0.033
  CI (99.9%): [3.123, 4.334] (assumes normal distribution)


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
# Warmup Iteration   1: 7.739 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.009 ms/op
Iteration   1: 3.161 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  10.371 ms/op
                 createUser·p0.9999: 22.282 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  10.650 ms/op
                 createUser·p0.9999: 23.429 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 3.163 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  9.027 ms/op
                 createUser·p0.9999: 17.750 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301112
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23503 
    [ 2.500,  5.000) = 271573 
    [ 5.000,  7.500) = 5368 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     22.803 ms/op
     p(99.9990) =     23.789 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 6.957 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.121 ms/op
                 existUser·p0.95:   3.289 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  9.747 ms/op
                 existUser·p0.9999: 19.538 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 20.256 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315605
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23912 
    [ 2.500,  5.000) = 287695 
    [ 5.000,  7.500) = 3290 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     21.576 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 7.377 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  18.219 ms/op
                 getUser·p0.9999: 20.121 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  11.869 ms/op
                 getUser·p0.9999: 26.420 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.177 ms/op
                 getUser·p0.999:  10.616 ms/op
                 getUser·p0.9999: 20.811 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297044
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17094 
    [ 2.500,  5.000) = 272465 
    [ 5.000,  7.500) = 6237 
    [ 7.500, 10.000) = 773 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.042 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     16.148 ms/op
     p(99.9900) =     24.923 ms/op
     p(99.9990) =     27.068 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 8.549 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.011 ms/op
Iteration   1: 3.655 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.104 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.713 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.925 ms/op
                 listUser·p0.999:  12.763 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.729 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.671 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259427
  mean =      3.699 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 252426 
    [ 5.000,  7.500) = 5040 
    [ 7.500, 10.000) = 1203 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     20.389 ms/op
     p(99.9990) =     22.855 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.978 ± 4.989  ops/ms
ClientPb.existUser                       thrpt       3  10.369 ± 7.271  ops/ms
ClientPb.getUser                         thrpt       3   9.999 ± 4.542  ops/ms
ClientPb.listUser                        thrpt       3   8.683 ± 0.690  ops/ms
ClientPb.createUser                       avgt       3   3.208 ± 2.314   ms/op
ClientPb.existUser                        avgt       3   3.056 ± 1.899   ms/op
ClientPb.getUser                          avgt       3   3.201 ± 1.301   ms/op
ClientPb.listUser                         avgt       3   3.729 ± 0.605   ms/op
ClientPb.createUser                     sample  301112   3.183 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.025           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.371           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.379           ms/op
ClientPb.existUser                      sample  315605   3.042 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.292           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.748           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  297044   3.231 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.210           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.042           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.148           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.923           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.165           ms/op
ClientPb.listUser                       sample  259427   3.699 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
