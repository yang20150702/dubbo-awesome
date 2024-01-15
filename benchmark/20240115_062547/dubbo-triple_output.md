# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.057 ops/ms
# Warmup Iteration   2: 12.141 ops/ms
# Warmup Iteration   3: 12.404 ops/ms
Iteration   1: 12.593 ops/ms
Iteration   2: 12.817 ops/ms
Iteration   3: 12.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.735 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (12.593, 12.735, 12.817), stdev = 0.124
  CI (99.9%): [10.474, 14.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.152 ops/ms
# Warmup Iteration   2: 13.321 ops/ms
# Warmup Iteration   3: 13.305 ops/ms
Iteration   1: 13.160 ops/ms
Iteration   2: 13.343 ops/ms
Iteration   3: 13.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.213 ±(99.9%) 2.053 ops/ms [Average]
  (min, avg, max) = (13.138, 13.213, 13.343), stdev = 0.113
  CI (99.9%): [11.161, 15.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ops/ms
# Warmup Iteration   2: 12.622 ops/ms
# Warmup Iteration   3: 12.790 ops/ms
Iteration   1: 12.956 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 13.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.907 ±(99.9%) 2.305 ops/ms [Average]
  (min, avg, max) = (12.764, 12.907, 13.002), stdev = 0.126
  CI (99.9%): [10.602, 15.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.988 ops/ms
# Warmup Iteration   2: 10.686 ops/ms
# Warmup Iteration   3: 10.721 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.746 ±(99.9%) 0.851 ops/ms [Average]
  (min, avg, max) = (10.708, 10.746, 10.798), stdev = 0.047
  CI (99.9%): [9.895, 11.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.586 ±(99.9%) 0.005 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (2.513, 2.540, 2.586), stdev = 0.040
  CI (99.9%): [1.804, 3.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.528 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.421 ±(99.9%) 0.003 ms/op
Iteration   3: 2.428 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.423 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.421, 2.423, 2.428), stdev = 0.004
  CI (99.9%): [2.354, 2.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.003 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
Iteration   3: 2.473 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.473, 2.479, 2.485), stdev = 0.006
  CI (99.9%): [2.366, 2.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (3.006, 3.015, 3.027), stdev = 0.011
  CI (99.9%): [2.822, 3.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  11.198 ms/op
                 createUser·p0.9999: 13.091 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.542 ms/op
                 createUser·p0.999:  10.338 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  8.382 ms/op
                 createUser·p0.9999: 11.808 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380239
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 182273 
    [ 2.500,  3.750) = 193600 
    [ 3.750,  5.000) = 3285 
    [ 5.000,  6.250) = 556 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 154 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.520 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.964 ms/op
                 existUser·p0.9999: 13.793 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  6.757 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  7.421 ms/op
                 existUser·p0.9999: 12.536 ms/op
                 existUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389235
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 190247 
    [ 2.500,  3.750) = 195739 
    [ 3.750,  5.000) = 2415 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.632 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     13.208 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.667 ms/op
                 getUser·p0.999:  9.821 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  9.357 ms/op
                 getUser·p0.9999: 12.503 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  5.299 ms/op
                 getUser·p0.9999: 11.036 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381709
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 188683 
    [ 2.500,  3.750) = 188573 
    [ 3.750,  5.000) = 3348 
    [ 5.000,  6.250) = 695 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      6.155 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     13.772 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.733 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.379 ms/op
                 listUser·p0.9999: 11.273 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.731 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.885 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 11.787 ms/op
                 listUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318225
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 92882 
    [ 2.500,  3.750) = 186463 
    [ 3.750,  5.000) = 32119 
    [ 5.000,  6.250) = 5361 
    [ 6.250,  7.500) = 614 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.548 ms/op
     p(99.9900) =     11.606 ms/op
     p(99.9990) =     11.959 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.735 ± 2.261  ops/ms
ClientPb.existUser                       thrpt       3  13.213 ± 2.053  ops/ms
ClientPb.getUser                         thrpt       3  12.907 ± 2.305  ops/ms
ClientPb.listUser                        thrpt       3  10.746 ± 0.851  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.736   ms/op
ClientPb.existUser                        avgt       3   2.423 ± 0.069   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.113   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.193   ms/op
ClientPb.createUser                     sample  380239   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.803           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.747           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.943           ms/op
ClientPb.existUser                      sample  389235   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.632           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.152           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.208           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.385           ms/op
ClientPb.getUser                        sample  381709   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.898           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.155           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.829           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  318225   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.548           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.606           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.304           ms/op
