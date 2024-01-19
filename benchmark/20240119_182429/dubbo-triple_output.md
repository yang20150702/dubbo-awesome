# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.911 ops/ms
# Warmup Iteration   2: 11.891 ops/ms
# Warmup Iteration   3: 12.240 ops/ms
Iteration   1: 12.597 ops/ms
Iteration   2: 12.777 ops/ms
Iteration   3: 12.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.715 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (12.597, 12.715, 12.777), stdev = 0.102
  CI (99.9%): [10.850, 14.580] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.001 ops/ms
# Warmup Iteration   2: 12.926 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 12.990 ops/ms
Iteration   2: 13.021 ops/ms
Iteration   3: 12.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.998 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (12.985, 12.998, 13.021), stdev = 0.019
  CI (99.9%): [12.646, 13.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.053 ops/ms
# Warmup Iteration   2: 12.574 ops/ms
# Warmup Iteration   3: 12.618 ops/ms
Iteration   1: 12.856 ops/ms
Iteration   2: 12.741 ops/ms
Iteration   3: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.775 ±(99.9%) 1.285 ops/ms [Average]
  (min, avg, max) = (12.728, 12.775, 12.856), stdev = 0.070
  CI (99.9%): [11.490, 14.060] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.864 ops/ms
# Warmup Iteration   2: 10.307 ops/ms
# Warmup Iteration   3: 10.473 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.535 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (10.478, 10.535, 10.564), stdev = 0.050
  CI (99.9%): [9.630, 11.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.004 ms/op
Iteration   1: 2.583 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.562 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.543, 2.562, 2.583), stdev = 0.020
  CI (99.9%): [2.191, 2.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.508 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.505, 2.508, 2.514), stdev = 0.005
  CI (99.9%): [2.416, 2.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.505 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.492, 2.505, 2.516), stdev = 0.012
  CI (99.9%): [2.282, 2.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (3.001, 3.007, 3.013), stdev = 0.006
  CI (99.9%): [2.897, 3.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.693 ms/op
                 createUser·p0.999:  10.945 ms/op
                 createUser·p0.9999: 12.940 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.510 ms/op
                 createUser·p0.999:  9.132 ms/op
                 createUser·p0.9999: 12.586 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 10.892 ms/op
                 createUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381314
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 183744 
    [ 2.500,  3.750) = 194152 
    [ 3.750,  5.000) = 2682 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 152 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     12.597 ms/op
     p(99.9990) =     13.145 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.384 ms/op
                 existUser·p0.9999: 13.912 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.856 ms/op
                 existUser·p0.999:  7.075 ms/op
                 existUser·p0.9999: 12.551 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.013 ms/op
                 existUser·p0.9999: 12.189 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389296
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 192617 
    [ 2.500,  3.750) = 192997 
    [ 3.750,  5.000) = 2645 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.065 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.127 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  5.588 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.578 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.482 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  7.070 ms/op
                 getUser·p0.9999: 12.177 ms/op
                 getUser·p1.00:   12.665 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  9.036 ms/op
                 getUser·p0.9999: 11.559 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381224
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 186218 
    [ 2.500,  3.750) = 188490 
    [ 3.750,  5.000) = 5181 
    [ 5.000,  6.250) = 729 
    [ 6.250,  7.500) = 202 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      6.959 ms/op
     p(99.9900) =     13.201 ms/op
     p(99.9990) =     13.847 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.008 ms/op
Iteration   1: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.985 ms/op
                 listUser·p0.9999: 16.531 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.582 ms/op
                 listUser·p0.9999: 11.049 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.116 ms/op
                 listUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317593
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 93661 
    [ 2.500,  3.750) = 183964 
    [ 3.750,  5.000) = 31831 
    [ 5.000,  6.250) = 6559 
    [ 6.250,  7.500) = 791 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     15.454 ms/op
     p(99.9990) =     16.736 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.715 ± 1.865  ops/ms
ClientPb.existUser                       thrpt       3  12.998 ± 0.352  ops/ms
ClientPb.getUser                         thrpt       3  12.775 ± 1.285  ops/ms
ClientPb.listUser                        thrpt       3  10.535 ± 0.905  ops/ms
ClientPb.createUser                       avgt       3   2.562 ± 0.371   ms/op
ClientPb.existUser                        avgt       3   2.508 ± 0.092   ms/op
ClientPb.getUser                          avgt       3   2.505 ± 0.223   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.110   ms/op
ClientPb.createUser                     sample  381314   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.597           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.435           ms/op
ClientPb.existUser                      sample  389296   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.914           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.065           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  381224   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.959           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.201           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  317593   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.454           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.974           ms/op
