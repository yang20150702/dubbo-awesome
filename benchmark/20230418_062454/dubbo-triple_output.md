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
# Warmup Iteration   1: 2.436 ops/ms
# Warmup Iteration   2: 5.709 ops/ms
# Warmup Iteration   3: 9.522 ops/ms
Iteration   1: 9.932 ops/ms
Iteration   2: 9.814 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.962 ±(99.9%) 3.012 ops/ms [Average]
  (min, avg, max) = (9.814, 9.962, 10.141), stdev = 0.165
  CI (99.9%): [6.950, 12.975] (assumes normal distribution)


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
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 8.890 ops/ms
# Warmup Iteration   3: 9.728 ops/ms
Iteration   1: 9.786 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.178 ±(99.9%) 6.333 ops/ms [Average]
  (min, avg, max) = (9.786, 10.178, 10.448), stdev = 0.347
  CI (99.9%): [3.844, 16.511] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ops/ms
# Warmup Iteration   2: 8.874 ops/ms
# Warmup Iteration   3: 9.131 ops/ms
Iteration   1: 9.873 ops/ms
Iteration   2: 10.399 ops/ms
Iteration   3: 10.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.095 ±(99.9%) 4.966 ops/ms [Average]
  (min, avg, max) = (9.873, 10.095, 10.399), stdev = 0.272
  CI (99.9%): [5.130, 15.061] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.352 ops/ms
# Warmup Iteration   2: 7.993 ops/ms
# Warmup Iteration   3: 8.638 ops/ms
Iteration   1: 8.562 ops/ms
Iteration   2: 8.497 ops/ms
Iteration   3: 8.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.512 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (8.476, 8.512, 8.562), stdev = 0.045
  CI (99.9%): [7.694, 9.329] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.669 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
Iteration   1: 3.487 ±(99.9%) 0.002 ms/op
Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
Iteration   3: 3.291 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.304 ±(99.9%) 3.206 ms/op [Average]
  (min, avg, max) = (3.136, 3.304, 3.487), stdev = 0.176
  CI (99.9%): [0.098, 6.510] (assumes normal distribution)


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
# Warmup Iteration   1: 7.847 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.004 ms/op
Iteration   1: 3.112 ±(99.9%) 0.005 ms/op
Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
Iteration   3: 3.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.081 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.045, 3.081, 3.112), stdev = 0.034
  CI (99.9%): [2.467, 3.695] (assumes normal distribution)


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
# Warmup Iteration   1: 7.296 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.005 ms/op
Iteration   1: 3.191 ±(99.9%) 0.003 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.303 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.210 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (3.135, 3.210, 3.303), stdev = 0.086
  CI (99.9%): [1.648, 4.772] (assumes normal distribution)


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
# Warmup Iteration   1: 10.200 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.005 ms/op
Iteration   1: 3.813 ±(99.9%) 0.007 ms/op
Iteration   2: 3.906 ±(99.9%) 0.009 ms/op
Iteration   3: 3.762 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.827 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (3.762, 3.827, 3.906), stdev = 0.073
  CI (99.9%): [2.492, 5.162] (assumes normal distribution)


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
# Warmup Iteration   1: 8.713 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.009 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.215 ms/op
                 createUser·p0.95:   3.428 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  19.072 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  14.156 ms/op
                 createUser·p0.9999: 20.504 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 309104
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18487 
    [ 2.500,  5.000) = 287091 
    [ 5.000,  7.500) = 2744 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     14.562 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.556 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.594 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.008 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.393 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   29.196 ms/op

Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.281 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 22.063 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  11.195 ms/op
                 existUser·p0.9999: 20.461 ms/op
                 existUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313005
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23459 
    [ 2.500,  5.000) = 286180 
    [ 5.000,  7.500) = 2739 
    [ 7.500, 10.000) = 295 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =     11.009 ms/op
     p(99.9900) =     27.112 ms/op
     p(99.9990) =     28.856 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 7.997 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.009 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  16.597 ms/op
                 getUser·p0.9999: 18.546 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  17.585 ms/op
                 getUser·p0.9999: 20.830 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  10.371 ms/op
                 getUser·p0.9999: 18.589 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 306868
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9854 
    [ 2.500,  5.000) = 292117 
    [ 5.000,  7.500) = 4136 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     20.228 ms/op
     p(99.9990) =     21.231 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 9.129 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.009 ms/op
Iteration   1: 3.804 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.678 ms/op
                 listUser·p0.999:  13.892 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.404 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.699 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.222 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256170
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 246176 
    [ 5.000,  7.500) = 7895 
    [ 7.500, 10.000) = 1239 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.962 ± 3.012  ops/ms
ClientPb.existUser                       thrpt       3  10.178 ± 6.333  ops/ms
ClientPb.getUser                         thrpt       3  10.095 ± 4.966  ops/ms
ClientPb.listUser                        thrpt       3   8.512 ± 0.818  ops/ms
ClientPb.createUser                       avgt       3   3.304 ± 3.206   ms/op
ClientPb.existUser                        avgt       3   3.081 ± 0.614   ms/op
ClientPb.getUser                          avgt       3   3.210 ± 1.562   ms/op
ClientPb.listUser                         avgt       3   3.827 ± 1.335   ms/op
ClientPb.createUser                     sample  309104   3.104 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.053           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.562           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.103           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  313005   3.066 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.814           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.054           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.009           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.112           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196           ms/op
ClientPb.getUser                        sample  306868   3.125 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.974           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.893           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.228           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.299           ms/op
ClientPb.listUser                       sample  256170   3.745 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.675           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.675           ms/op
