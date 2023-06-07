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
# Warmup Iteration   1: 2.245 ops/ms
# Warmup Iteration   2: 5.858 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 9.151 ops/ms
Iteration   2: 9.521 ops/ms
Iteration   3: 9.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.346 ±(99.9%) 3.392 ops/ms [Average]
  (min, avg, max) = (9.151, 9.346, 9.521), stdev = 0.186
  CI (99.9%): [5.953, 12.738] (assumes normal distribution)


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
# Warmup Iteration   1: 2.844 ops/ms
# Warmup Iteration   2: 8.436 ops/ms
# Warmup Iteration   3: 9.921 ops/ms
Iteration   1: 9.941 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.903 ±(99.9%) 2.467 ops/ms [Average]
  (min, avg, max) = (9.753, 9.903, 10.016), stdev = 0.135
  CI (99.9%): [7.437, 12.370] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.043 ops/ms
# Warmup Iteration   2: 8.515 ops/ms
# Warmup Iteration   3: 9.390 ops/ms
Iteration   1: 9.609 ops/ms
Iteration   2: 9.199 ops/ms
Iteration   3: 9.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.379 ±(99.9%) 3.824 ops/ms [Average]
  (min, avg, max) = (9.199, 9.379, 9.609), stdev = 0.210
  CI (99.9%): [5.555, 13.203] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.143 ops/ms
# Warmup Iteration   2: 7.251 ops/ms
# Warmup Iteration   3: 8.029 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 8.015 ops/ms
Iteration   3: 8.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.149 ±(99.9%) 2.594 ops/ms [Average]
  (min, avg, max) = (8.015, 8.149, 8.298), stdev = 0.142
  CI (99.9%): [5.555, 10.743] (assumes normal distribution)


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
# Warmup Iteration   1: 10.436 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.010 ms/op
Iteration   1: 3.381 ±(99.9%) 0.013 ms/op
Iteration   2: 3.427 ±(99.9%) 0.007 ms/op
Iteration   3: 3.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.445 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (3.381, 3.445, 3.527), stdev = 0.075
  CI (99.9%): [2.084, 4.806] (assumes normal distribution)


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
# Warmup Iteration   1: 9.392 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.006 ms/op
Iteration   1: 3.243 ±(99.9%) 0.005 ms/op
Iteration   2: 3.198 ±(99.9%) 0.011 ms/op
Iteration   3: 3.208 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.216 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.198, 3.216, 3.243), stdev = 0.023
  CI (99.9%): [2.789, 3.644] (assumes normal distribution)


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
# Warmup Iteration   1: 8.119 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.003 ms/op
Iteration   1: 3.370 ±(99.9%) 0.007 ms/op
Iteration   2: 3.300 ±(99.9%) 0.007 ms/op
Iteration   3: 3.386 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.352 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (3.300, 3.352, 3.386), stdev = 0.046
  CI (99.9%): [2.512, 4.192] (assumes normal distribution)


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
# Warmup Iteration   1: 9.940 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
Iteration   1: 3.770 ±(99.9%) 0.012 ms/op
Iteration   2: 3.962 ±(99.9%) 0.008 ms/op
Iteration   3: 3.837 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.857 ±(99.9%) 1.774 ms/op [Average]
  (min, avg, max) = (3.770, 3.857, 3.962), stdev = 0.097
  CI (99.9%): [2.083, 5.631] (assumes normal distribution)


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
# Warmup Iteration   1: 9.432 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.011 ms/op
Iteration   1: 3.386 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 24.549 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.502 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.980 ms/op
                 createUser·p0.999:  21.909 ms/op
                 createUser·p0.9999: 29.024 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   3: 3.543 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  15.425 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276144
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8948 
    [ 2.500,  5.000) = 258547 
    [ 5.000,  7.500) = 7239 
    [ 7.500, 10.000) = 959 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     16.507 ms/op
     p(99.9900) =     26.913 ms/op
     p(99.9990) =     29.245 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 8.336 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.007 ms/op
Iteration   1: 3.382 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   5.863 ms/op
                 existUser·p0.999:  18.790 ms/op
                 existUser·p0.9999: 23.468 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 3.315 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  16.675 ms/op
                 existUser·p0.9999: 24.882 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  12.612 ms/op
                 existUser·p0.9999: 25.891 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288297
  mean =      3.328 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17093 
    [ 2.500,  5.000) = 266300 
    [ 5.000,  7.500) = 3861 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 195 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     17.111 ms/op
     p(99.9900) =     24.909 ms/op
     p(99.9990) =     26.881 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 8.761 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
Iteration   1: 3.447 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  19.013 ms/op
                 getUser·p0.9999: 21.689 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 3.483 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.843 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  18.383 ms/op
                 getUser·p0.9999: 29.917 ms/op
                 getUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275999
  mean =      3.478 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10568 
    [ 2.500,  5.000) = 257428 
    [ 5.000,  7.500) = 6907 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     29.255 ms/op
     p(99.9990) =     30.348 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 11.019 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.013 ms/op
Iteration   1: 3.933 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 22.695 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   2: 4.028 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  15.307 ms/op
                 listUser·p0.9999: 17.533 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 3.888 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242948
  mean =      3.949 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 234664 
    [ 5.000,  7.500) = 6579 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     21.087 ms/op
     p(99.9990) =     23.158 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.346 ± 3.392  ops/ms
ClientPb.existUser                       thrpt       3   9.903 ± 2.467  ops/ms
ClientPb.getUser                         thrpt       3   9.379 ± 3.824  ops/ms
ClientPb.listUser                        thrpt       3   8.149 ± 2.594  ops/ms
ClientPb.createUser                       avgt       3   3.445 ± 1.361   ms/op
ClientPb.existUser                        avgt       3   3.216 ± 0.427   ms/op
ClientPb.getUser                          avgt       3   3.352 ± 0.840   ms/op
ClientPb.listUser                         avgt       3   3.857 ± 1.774   ms/op
ClientPb.createUser                     sample  276144   3.476 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.507           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.913           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  288297   3.328 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.111           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.909           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  275999   3.478 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.337           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.255           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  242948   3.949 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.853           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.548           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.087           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.462           ms/op
