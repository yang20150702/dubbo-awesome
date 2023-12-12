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
# Warmup Iteration   1: 4.933 ops/ms
# Warmup Iteration   2: 12.203 ops/ms
# Warmup Iteration   3: 12.379 ops/ms
Iteration   1: 12.387 ops/ms
Iteration   2: 12.418 ops/ms
Iteration   3: 12.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.402 ±(99.9%) 0.290 ops/ms [Average]
  (min, avg, max) = (12.387, 12.402, 12.418), stdev = 0.016
  CI (99.9%): [12.112, 12.691] (assumes normal distribution)


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
# Warmup Iteration   1: 8.665 ops/ms
# Warmup Iteration   2: 12.923 ops/ms
# Warmup Iteration   3: 13.011 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.934 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.906 ±(99.9%) 0.584 ops/ms [Average]
  (min, avg, max) = (12.871, 12.906, 12.934), stdev = 0.032
  CI (99.9%): [12.323, 13.490] (assumes normal distribution)


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
# Warmup Iteration   1: 7.808 ops/ms
# Warmup Iteration   2: 12.236 ops/ms
# Warmup Iteration   3: 12.646 ops/ms
Iteration   1: 12.659 ops/ms
Iteration   2: 12.474 ops/ms
Iteration   3: 12.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.618 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (12.474, 12.618, 12.722), stdev = 0.129
  CI (99.9%): [10.264, 14.973] (assumes normal distribution)


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
# Warmup Iteration   1: 6.501 ops/ms
# Warmup Iteration   2: 10.564 ops/ms
# Warmup Iteration   3: 10.634 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.649 ±(99.9%) 1.454 ops/ms [Average]
  (min, avg, max) = (10.597, 10.649, 10.741), stdev = 0.080
  CI (99.9%): [9.195, 12.103] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.527 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.506, 2.527, 2.547), stdev = 0.020
  CI (99.9%): [2.153, 2.901] (assumes normal distribution)


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.003 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.465, 2.472, 2.476), stdev = 0.006
  CI (99.9%): [2.357, 2.587] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.003 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (2.469, 2.496, 2.539), stdev = 0.038
  CI (99.9%): [1.800, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
Iteration   3: 3.011 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.001, 3.010, 3.020), stdev = 0.009
  CI (99.9%): [2.840, 3.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  10.968 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  7.837 ms/op
                 createUser·p0.9999: 12.307 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  8.133 ms/op
                 createUser·p0.9999: 10.600 ms/op
                 createUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385321
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 188768 
    [ 2.500,  3.750) = 192742 
    [ 3.750,  5.000) = 3099 
    [ 5.000,  6.250) = 220 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.124 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     14.306 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  5.417 ms/op
                 existUser·p0.9999: 13.303 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.322 ms/op
                 existUser·p0.999:  5.717 ms/op
                 existUser·p0.9999: 12.910 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 11.381 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389296
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 194280 
    [ 2.500,  3.750) = 192750 
    [ 3.750,  5.000) = 1671 
    [ 5.000,  6.250) = 173 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      6.160 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.940 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  11.401 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.878 ms/op
                 getUser·p0.999:  9.442 ms/op
                 getUser·p0.9999: 13.728 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  8.361 ms/op
                 getUser·p0.9999: 10.788 ms/op
                 getUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375674
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 184658 
    [ 2.500,  3.750) = 185802 
    [ 3.750,  5.000) = 4252 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     13.229 ms/op
     p(99.9990) =     14.270 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.643 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.008 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.770 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.476 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 12.510 ms/op
                 listUser·p1.00:   15.090 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.769 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320513
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 95035 
    [ 2.500,  3.750) = 187246 
    [ 3.750,  5.000) = 30545 
    [ 5.000,  6.250) = 6116 
    [ 6.250,  7.500) = 729 
    [ 7.500,  8.750) = 277 
    [ 8.750, 10.000) = 270 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.158 ms/op
     p(99.9990) =     13.920 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.402 ± 0.290  ops/ms
ClientPb.existUser                       thrpt       3  12.906 ± 0.584  ops/ms
ClientPb.getUser                         thrpt       3  12.618 ± 2.355  ops/ms
ClientPb.listUser                        thrpt       3  10.649 ± 1.454  ops/ms
ClientPb.createUser                       avgt       3   2.527 ± 0.374   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.115   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.696   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.171   ms/op
ClientPb.createUser                     sample  385321   2.489 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.124           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.763           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  389296   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.972           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.160           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  375674   2.553 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.949           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.421           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.229           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  320513   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.844           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.158           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.090           ms/op
