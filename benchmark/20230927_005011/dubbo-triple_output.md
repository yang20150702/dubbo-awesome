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
# Warmup Iteration   1: 2.155 ops/ms
# Warmup Iteration   2: 5.239 ops/ms
# Warmup Iteration   3: 8.853 ops/ms
Iteration   1: 9.350 ops/ms
Iteration   2: 9.081 ops/ms
Iteration   3: 9.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.203 ±(99.9%) 2.486 ops/ms [Average]
  (min, avg, max) = (9.081, 9.203, 9.350), stdev = 0.136
  CI (99.9%): [6.718, 11.689] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 8.811 ops/ms
# Warmup Iteration   3: 9.443 ops/ms
Iteration   1: 9.626 ops/ms
Iteration   2: 9.695 ops/ms
Iteration   3: 9.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.671 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (9.626, 9.671, 9.695), stdev = 0.039
  CI (99.9%): [8.958, 10.385] (assumes normal distribution)


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
# Warmup Iteration   1: 2.797 ops/ms
# Warmup Iteration   2: 8.173 ops/ms
# Warmup Iteration   3: 9.251 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 9.359 ops/ms
Iteration   3: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.393 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (9.344, 9.393, 9.476), stdev = 0.072
  CI (99.9%): [8.072, 10.714] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 7.222 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.864 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.875 ±(99.9%) 0.826 ops/ms [Average]
  (min, avg, max) = (7.836, 7.875, 7.925), stdev = 0.045
  CI (99.9%): [7.049, 8.701] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.741 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.004 ms/op
Iteration   1: 3.552 ±(99.9%) 0.003 ms/op
Iteration   2: 3.418 ±(99.9%) 0.007 ms/op
Iteration   3: 3.404 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.458 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (3.404, 3.458, 3.552), stdev = 0.082
  CI (99.9%): [1.971, 4.945] (assumes normal distribution)


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
# Warmup Iteration   1: 8.294 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.002 ms/op
Iteration   1: 3.307 ±(99.9%) 0.004 ms/op
Iteration   2: 3.231 ±(99.9%) 0.003 ms/op
Iteration   3: 3.419 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.319 ±(99.9%) 1.725 ms/op [Average]
  (min, avg, max) = (3.231, 3.319, 3.419), stdev = 0.095
  CI (99.9%): [1.594, 5.044] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.941 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.004 ms/op
Iteration   1: 3.525 ±(99.9%) 0.003 ms/op
Iteration   2: 3.468 ±(99.9%) 0.003 ms/op
Iteration   3: 3.449 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.481 ±(99.9%) 0.718 ms/op [Average]
  (min, avg, max) = (3.449, 3.481, 3.525), stdev = 0.039
  CI (99.9%): [2.762, 4.199] (assumes normal distribution)


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
# Warmup Iteration   1: 10.166 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.005 ms/op
Iteration   1: 4.091 ±(99.9%) 0.005 ms/op
Iteration   2: 4.115 ±(99.9%) 0.005 ms/op
Iteration   3: 4.090 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.099 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (4.090, 4.099, 4.115), stdev = 0.014
  CI (99.9%): [3.840, 4.358] (assumes normal distribution)


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
# Warmup Iteration   1: 9.266 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
Iteration   1: 3.574 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  12.247 ms/op
                 createUser·p0.9999: 22.775 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.480 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  21.369 ms/op
                 createUser·p0.9999: 25.284 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  19.156 ms/op
                 createUser·p0.9999: 26.363 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273856
  mean =      3.507 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3897 
    [ 2.500,  5.000) = 264312 
    [ 5.000,  7.500) = 4502 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     16.524 ms/op
     p(99.9900) =     25.514 ms/op
     p(99.9990) =     27.544 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 7.748 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.008 ms/op
Iteration   1: 3.362 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 24.329 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 30.548 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282589
  mean =      3.396 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5343 
    [ 2.500,  5.000) = 272438 
    [ 5.000,  7.500) = 3627 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.229 ms/op
     p(99.9900) =     29.489 ms/op
     p(99.9990) =     30.940 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 9.285 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.012 ms/op
Iteration   1: 3.616 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  14.025 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.480 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  21.368 ms/op
                 getUser·p0.9999: 25.614 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  18.555 ms/op
                 getUser·p0.9999: 25.821 ms/op
                 getUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272715
  mean =      3.518 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8988 
    [ 2.500,  5.000) = 256854 
    [ 5.000,  7.500) = 5649 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.151 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 10.881 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.012 ms/op
Iteration   1: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  18.601 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.979 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 17.562 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 4.089 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  15.717 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238123
  mean =      4.034 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 230161 
    [ 5.000,  7.500) = 6155 
    [ 7.500, 10.000) = 1041 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     20.820 ms/op
     p(99.9990) =     22.487 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.203 ± 2.486  ops/ms
ClientPb.existUser                       thrpt       3   9.671 ± 0.713  ops/ms
ClientPb.getUser                         thrpt       3   9.393 ± 1.321  ops/ms
ClientPb.listUser                        thrpt       3   7.875 ± 0.826  ops/ms
ClientPb.createUser                       avgt       3   3.458 ± 1.487   ms/op
ClientPb.existUser                        avgt       3   3.319 ± 1.725   ms/op
ClientPb.getUser                          avgt       3   3.481 ± 0.718   ms/op
ClientPb.listUser                         avgt       3   4.099 ± 0.259   ms/op
ClientPb.createUser                     sample  273856   3.507 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.305           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.524           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.514           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.820           ms/op
ClientPb.existUser                      sample  282589   3.396 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.323           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.229           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.489           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.359           ms/op
ClientPb.getUser                        sample  272715   3.518 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.079           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.151           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.231           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.246           ms/op
ClientPb.listUser                       sample  238123   4.034 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.303           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.155           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.820           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.643           ms/op
