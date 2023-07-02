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
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 6.238 ops/ms
# Warmup Iteration   3: 8.473 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.316 ops/ms
Iteration   3: 9.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.265 ±(99.9%) 2.307 ops/ms [Average]
  (min, avg, max) = (9.121, 9.265, 9.358), stdev = 0.126
  CI (99.9%): [6.958, 11.572] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.866 ops/ms
# Warmup Iteration   2: 8.476 ops/ms
# Warmup Iteration   3: 9.697 ops/ms
Iteration   1: 9.384 ops/ms
Iteration   2: 10.020 ops/ms
Iteration   3: 10.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.813 ±(99.9%) 6.776 ops/ms [Average]
  (min, avg, max) = (9.384, 9.813, 10.034), stdev = 0.371
  CI (99.9%): [3.036, 16.589] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.008 ops/ms
# Warmup Iteration   2: 8.274 ops/ms
# Warmup Iteration   3: 8.615 ops/ms
Iteration   1: 9.270 ops/ms
Iteration   2: 8.948 ops/ms
Iteration   3: 9.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.083 ±(99.9%) 3.048 ops/ms [Average]
  (min, avg, max) = (8.948, 9.083, 9.270), stdev = 0.167
  CI (99.9%): [6.035, 12.131] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.646 ops/ms
# Warmup Iteration   2: 7.325 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 8.032 ops/ms
Iteration   2: 7.905 ops/ms
Iteration   3: 8.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.027 ±(99.9%) 2.189 ops/ms [Average]
  (min, avg, max) = (7.905, 8.027, 8.145), stdev = 0.120
  CI (99.9%): [5.839, 10.216] (assumes normal distribution)


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
# Warmup Iteration   1: 10.742 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.008 ms/op
Iteration   1: 3.582 ±(99.9%) 0.004 ms/op
Iteration   2: 3.446 ±(99.9%) 0.007 ms/op
Iteration   3: 3.380 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.469 ±(99.9%) 1.883 ms/op [Average]
  (min, avg, max) = (3.380, 3.469, 3.582), stdev = 0.103
  CI (99.9%): [1.587, 5.352] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.586 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.007 ms/op
Iteration   1: 3.301 ±(99.9%) 0.010 ms/op
Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
Iteration   3: 3.270 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.265 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.222, 3.265, 3.301), stdev = 0.040
  CI (99.9%): [2.543, 3.986] (assumes normal distribution)


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
# Warmup Iteration   1: 9.400 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.010 ms/op
Iteration   1: 3.518 ±(99.9%) 0.005 ms/op
Iteration   2: 3.444 ±(99.9%) 0.004 ms/op
Iteration   3: 3.439 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (3.439, 3.467, 3.518), stdev = 0.044
  CI (99.9%): [2.664, 4.271] (assumes normal distribution)


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
# Warmup Iteration   1: 10.704 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.007 ms/op
Iteration   1: 3.946 ±(99.9%) 0.012 ms/op
Iteration   2: 3.996 ±(99.9%) 0.010 ms/op
Iteration   3: 3.969 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.970 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.946, 3.970, 3.996), stdev = 0.025
  CI (99.9%): [3.514, 4.426] (assumes normal distribution)


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
# Warmup Iteration   1: 10.124 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.011 ms/op
Iteration   1: 3.610 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  19.542 ms/op
                 createUser·p0.9999: 21.894 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.428 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  21.880 ms/op
                 createUser·p0.9999: 24.587 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  17.691 ms/op
                 createUser·p0.9999: 27.982 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276930
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7540 
    [ 2.500,  5.000) = 261265 
    [ 5.000,  7.500) = 6849 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     26.189 ms/op
     p(99.9990) =     28.760 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 9.020 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.010 ms/op
Iteration   1: 3.290 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 18.261 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 3.268 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.601 ms/op
                 existUser·p0.9999: 20.310 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   3: 3.312 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   6.089 ms/op
                 existUser·p0.999:  16.271 ms/op
                 existUser·p0.9999: 23.145 ms/op
                 existUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291786
  mean =      3.290 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7775 
    [ 2.500,  5.000) = 278908 
    [ 5.000,  7.500) = 4182 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.553 ms/op
     p(99.9900) =     21.621 ms/op
     p(99.9990) =     24.254 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 9.829 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.008 ms/op
Iteration   1: 3.479 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  18.993 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  22.254 ms/op
                 getUser·p0.9999: 27.483 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.383 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.846 ms/op
                 getUser·p0.999:  11.281 ms/op
                 getUser·p0.9999: 21.696 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279297
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2863 
    [ 2.500,  5.000) = 266565 
    [ 5.000,  7.500) = 8882 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.236 ms/op
     p(99.9900) =     26.816 ms/op
     p(99.9990) =     28.580 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 11.059 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.013 ms/op
Iteration   1: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 20.592 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.854 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.222 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 18.415 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.049 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239724
  mean =      4.000 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 230233 
    [ 5.000,  7.500) = 7238 
    [ 7.500, 10.000) = 1495 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.363 ms/op
     p(99.9000) =     16.110 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.265 ± 2.307  ops/ms
ClientPb.existUser                       thrpt       3   9.813 ± 6.776  ops/ms
ClientPb.getUser                         thrpt       3   9.083 ± 3.048  ops/ms
ClientPb.listUser                        thrpt       3   8.027 ± 2.189  ops/ms
ClientPb.createUser                       avgt       3   3.469 ± 1.883   ms/op
ClientPb.existUser                        avgt       3   3.265 ± 0.721   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 0.804   ms/op
ClientPb.listUser                         avgt       3   3.970 ± 0.456   ms/op
ClientPb.createUser                     sample  276930   3.466 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.255           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.186           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  291786   3.290 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.434           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.553           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.621           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.330           ms/op
ClientPb.getUser                        sample  279297   3.434 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.236           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.816           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.606           ms/op
ClientPb.listUser                       sample  239724   4.000 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.002           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.363           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.152           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.216           ms/op
