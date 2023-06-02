# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 5.854 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 9.263 ops/ms
Iteration   2: 9.263 ops/ms
Iteration   3: 9.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.281 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (9.263, 9.281, 9.316), stdev = 0.031
  CI (99.9%): [8.724, 9.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.035 ops/ms
# Warmup Iteration   2: 9.169 ops/ms
# Warmup Iteration   3: 9.624 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 10.000 ops/ms
Iteration   3: 9.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.956 ±(99.9%) 3.336 ops/ms [Average]
  (min, avg, max) = (9.756, 9.956, 10.113), stdev = 0.183
  CI (99.9%): [6.621, 13.292] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 8.946 ops/ms
# Warmup Iteration   3: 8.704 ops/ms
Iteration   1: 9.499 ops/ms
Iteration   2: 9.570 ops/ms
Iteration   3: 9.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.508 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (9.456, 9.508, 9.570), stdev = 0.057
  CI (99.9%): [8.465, 10.552] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 7.199 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 8.179 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.129 ±(99.9%) 3.794 ops/ms [Average]
  (min, avg, max) = (7.901, 8.129, 8.308), stdev = 0.208
  CI (99.9%): [4.335, 11.923] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.660 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.009 ms/op
Iteration   1: 3.371 ±(99.9%) 0.009 ms/op
Iteration   2: 3.425 ±(99.9%) 0.003 ms/op
Iteration   3: 3.387 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.394 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.371, 3.394, 3.425), stdev = 0.028
  CI (99.9%): [2.879, 3.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.548 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.006 ms/op
Iteration   1: 3.362 ±(99.9%) 0.003 ms/op
Iteration   2: 3.162 ±(99.9%) 0.003 ms/op
Iteration   3: 3.154 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 2.155 ms/op [Average]
  (min, avg, max) = (3.154, 3.226, 3.362), stdev = 0.118
  CI (99.9%): [1.071, 5.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.000 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.003 ms/op
Iteration   2: 3.327 ±(99.9%) 0.006 ms/op
Iteration   3: 3.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.432 ±(99.9%) 1.744 ms/op [Average]
  (min, avg, max) = (3.327, 3.432, 3.514), stdev = 0.096
  CI (99.9%): [1.688, 5.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.396 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.008 ms/op
Iteration   1: 3.853 ±(99.9%) 0.009 ms/op
Iteration   2: 3.976 ±(99.9%) 0.011 ms/op
Iteration   3: 3.822 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.884 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (3.822, 3.884, 3.976), stdev = 0.081
  CI (99.9%): [2.402, 5.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.381 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.013 ms/op
Iteration   1: 3.386 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  20.152 ms/op
                 createUser·p0.9999: 25.693 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  21.245 ms/op
                 createUser·p0.9999: 26.472 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  17.134 ms/op
                 createUser·p0.9999: 25.257 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284253
  mean =      3.374 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5585 
    [ 2.500,  5.000) = 272899 
    [ 5.000,  7.500) = 4702 
    [ 7.500, 10.000) = 636 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     19.423 ms/op
     p(99.9900) =     26.004 ms/op
     p(99.9990) =     27.825 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.626 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.363 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  11.352 ms/op
                 existUser·p0.9999: 25.395 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  16.172 ms/op
                 existUser·p0.9999: 24.583 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  16.803 ms/op
                 existUser·p0.9999: 28.839 ms/op
                 existUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286331
  mean =      3.350 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8770 
    [ 2.500,  5.000) = 272482 
    [ 5.000,  7.500) = 4161 
    [ 7.500, 10.000) = 523 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.609 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     26.489 ms/op
     p(99.9990) =     29.467 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.012 ms/op
Iteration   1: 3.320 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  17.198 ms/op
                 getUser·p0.9999: 36.200 ms/op
                 getUser·p1.00:   36.372 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  22.243 ms/op
                 getUser·p0.9999: 26.616 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 3.338 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.098 ms/op
                 getUser·p0.999:  20.488 ms/op
                 getUser·p0.9999: 27.722 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285822
  mean =      3.356 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2679 
    [ 2.500,  5.000) = 276267 
    [ 5.000,  7.500) = 5945 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     36.316 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.978 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.012 ms/op
Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 25.035 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 3.912 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 16.155 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   3: 3.951 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 16.712 ms/op
                 listUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242368
  mean =      3.959 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 234183 
    [ 5.000,  7.500) = 5952 
    [ 7.500, 10.000) = 1460 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     25.321 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.281 ± 0.557  ops/ms
ClientPb.existUser                       thrpt       3   9.956 ± 3.336  ops/ms
ClientPb.getUser                         thrpt       3   9.508 ± 1.044  ops/ms
ClientPb.listUser                        thrpt       3   8.129 ± 3.794  ops/ms
ClientPb.createUser                       avgt       3   3.394 ± 0.516   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 2.155   ms/op
ClientPb.getUser                          avgt       3   3.432 ± 1.744   ms/op
ClientPb.listUser                         avgt       3   3.884 ± 1.482   ms/op
ClientPb.createUser                     sample  284253   3.374 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.231           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.423           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.004           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  286331   3.350 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.569           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.609           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.303           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.489           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.688           ms/op
ClientPb.getUser                        sample  285822   3.356 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.389           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.372           ms/op
ClientPb.listUser                       sample  242368   3.959 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.577           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.592           ms/op
