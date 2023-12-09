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
# Warmup Iteration   1: 4.606 ops/ms
# Warmup Iteration   2: 12.156 ops/ms
# Warmup Iteration   3: 12.244 ops/ms
Iteration   1: 12.588 ops/ms
Iteration   2: 12.554 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.600 ±(99.9%) 0.969 ops/ms [Average]
  (min, avg, max) = (12.554, 12.600, 12.659), stdev = 0.053
  CI (99.9%): [11.632, 13.569] (assumes normal distribution)


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
# Warmup Iteration   1: 8.138 ops/ms
# Warmup Iteration   2: 12.730 ops/ms
# Warmup Iteration   3: 13.066 ops/ms
Iteration   1: 13.028 ops/ms
Iteration   2: 12.979 ops/ms
Iteration   3: 13.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.013 ±(99.9%) 0.527 ops/ms [Average]
  (min, avg, max) = (12.979, 13.013, 13.031), stdev = 0.029
  CI (99.9%): [12.486, 13.539] (assumes normal distribution)


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
# Warmup Iteration   1: 8.012 ops/ms
# Warmup Iteration   2: 12.589 ops/ms
# Warmup Iteration   3: 12.558 ops/ms
Iteration   1: 12.856 ops/ms
Iteration   2: 12.857 ops/ms
Iteration   3: 12.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.841 ±(99.9%) 0.473 ops/ms [Average]
  (min, avg, max) = (12.811, 12.841, 12.857), stdev = 0.026
  CI (99.9%): [12.369, 13.314] (assumes normal distribution)


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
# Warmup Iteration   1: 6.631 ops/ms
# Warmup Iteration   2: 10.417 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.628 ±(99.9%) 1.393 ops/ms [Average]
  (min, avg, max) = (10.549, 10.628, 10.701), stdev = 0.076
  CI (99.9%): [9.235, 12.020] (assumes normal distribution)


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.576 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.550 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.556 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.540, 2.556, 2.576), stdev = 0.019
  CI (99.9%): [2.215, 2.896] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.003 ms/op
Iteration   2: 2.470 ±(99.9%) 0.003 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.457, 2.473, 2.492), stdev = 0.018
  CI (99.9%): [2.151, 2.795] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.003 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.485, 2.493, 2.510), stdev = 0.014
  CI (99.9%): [2.240, 2.747] (assumes normal distribution)


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
Iteration   3: 3.025 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.017 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (3.010, 3.017, 3.025), stdev = 0.007
  CI (99.9%): [2.881, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.677 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  11.734 ms/op
                 createUser·p0.9999: 13.608 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  9.567 ms/op
                 createUser·p0.9999: 12.623 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.464 ms/op
                 createUser·p0.9999: 10.812 ms/op
                 createUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375092
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 177872 
    [ 2.500,  3.750) = 191859 
    [ 3.750,  5.000) = 4398 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.584 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.881 ms/op
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
# Warmup Iteration   1: 3.542 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  5.472 ms/op
                 existUser·p0.9999: 13.646 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.355 ms/op
                 existUser·p0.9999: 13.532 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  7.517 ms/op
                 existUser·p0.9999: 11.567 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390963
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 194288 
    [ 2.500,  3.750) = 193191 
    [ 3.750,  5.000) = 2744 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      6.193 ms/op
     p(99.9900) =     13.319 ms/op
     p(99.9990) =     14.635 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 13.604 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  7.404 ms/op
                 getUser·p0.9999: 12.472 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.173 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.054 ms/op
                 getUser·p0.9999: 10.797 ms/op
                 getUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383673
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 190188 
    [ 2.500,  3.750) = 188284 
    [ 3.750,  5.000) = 3866 
    [ 5.000,  6.250) = 817 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      8.066 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     13.735 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.338 ms/op
                 listUser·p0.9999: 13.328 ms/op
                 listUser·p1.00:   14.500 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  10.043 ms/op
                 listUser·p0.9999: 13.590 ms/op
                 listUser·p1.00:   14.057 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.852 ms/op
                 listUser·p0.9999: 13.007 ms/op
                 listUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315788
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 87770 
    [ 2.500,  3.750) = 187259 
    [ 3.750,  5.000) = 33100 
    [ 5.000,  6.250) = 6082 
    [ 6.250,  7.500) = 793 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.645 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     13.229 ms/op
     p(99.9990) =     14.088 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.600 ± 0.969  ops/ms
ClientPb.existUser                       thrpt       3  13.013 ± 0.527  ops/ms
ClientPb.getUser                         thrpt       3  12.841 ± 0.473  ops/ms
ClientPb.listUser                        thrpt       3  10.628 ± 1.393  ops/ms
ClientPb.createUser                       avgt       3   2.556 ± 0.341   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.322   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.254   ms/op
ClientPb.listUser                         avgt       3   3.017 ± 0.136   ms/op
ClientPb.createUser                     sample  375092   2.557 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.709           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.584           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.943           ms/op
ClientPb.existUser                      sample  390963   2.453 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.919           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.193           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.319           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  383673   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.628           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.066           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.878           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.828           ms/op
ClientPb.listUser                       sample  315788   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.873           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.645           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.229           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.500           ms/op
