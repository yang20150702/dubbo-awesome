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
# Warmup Iteration   1: 4.776 ops/ms
# Warmup Iteration   2: 12.152 ops/ms
# Warmup Iteration   3: 12.374 ops/ms
Iteration   1: 12.442 ops/ms
Iteration   2: 12.440 ops/ms
Iteration   3: 12.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.497 ±(99.9%) 1.781 ops/ms [Average]
  (min, avg, max) = (12.440, 12.497, 12.610), stdev = 0.098
  CI (99.9%): [10.716, 14.279] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.504 ops/ms
# Warmup Iteration   2: 13.242 ops/ms
# Warmup Iteration   3: 13.181 ops/ms
Iteration   1: 13.220 ops/ms
Iteration   2: 13.312 ops/ms
Iteration   3: 13.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.238 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (13.181, 13.238, 13.312), stdev = 0.068
  CI (99.9%): [12.005, 14.470] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.118 ops/ms
# Warmup Iteration   2: 12.639 ops/ms
# Warmup Iteration   3: 12.832 ops/ms
Iteration   1: 13.104 ops/ms
Iteration   2: 12.969 ops/ms
Iteration   3: 12.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.943 ±(99.9%) 3.203 ops/ms [Average]
  (min, avg, max) = (12.755, 12.943, 13.104), stdev = 0.176
  CI (99.9%): [9.739, 16.146] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.935 ops/ms
# Warmup Iteration   2: 10.658 ops/ms
# Warmup Iteration   3: 10.688 ops/ms
Iteration   1: 10.788 ops/ms
Iteration   2: 10.776 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.784 ±(99.9%) 0.135 ops/ms [Average]
  (min, avg, max) = (10.776, 10.784, 10.789), stdev = 0.007
  CI (99.9%): [10.650, 10.919] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.509, 2.518, 2.534), stdev = 0.014
  CI (99.9%): [2.262, 2.773] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.003 ms/op
Iteration   3: 2.460 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.445, 2.458, 2.468), stdev = 0.012
  CI (99.9%): [2.242, 2.673] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.475 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.459, 2.475, 2.492), stdev = 0.016
  CI (99.9%): [2.175, 2.775] (assumes normal distribution)


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.004 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
Iteration   3: 2.973 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.984 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.973, 2.984, 2.992), stdev = 0.010
  CI (99.9%): [2.807, 3.160] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.573 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  11.473 ms/op
                 createUser·p0.9999: 14.821 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 12.247 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  8.031 ms/op
                 createUser·p0.9999: 12.165 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374672
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 178483 
    [ 2.500,  3.750) = 192000 
    [ 3.750,  5.000) = 3482 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.798 ms/op
     p(99.9000) =      8.137 ms/op
     p(99.9900) =     14.116 ms/op
     p(99.9990) =     15.434 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.486 ms/op
                 existUser·p0.9999: 14.172 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  8.905 ms/op
                 existUser·p0.9999: 13.828 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  9.465 ms/op
                 existUser·p0.9999: 12.211 ms/op
                 existUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384661
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 190237 
    [ 2.500,  3.750) = 191107 
    [ 3.750,  5.000) = 2574 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.737 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.388 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.604 ±(99.9%) 0.006 ms/op
Iteration   1: 2.579 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.802 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 13.756 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.602 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.330 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 13.545 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.158 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  9.127 ms/op
                 getUser·p0.9999: 14.110 ms/op
                 getUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 370771
  mean =      2.587 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 178055 
    [ 2.500,  3.750) = 186901 
    [ 3.750,  5.000) = 4459 
    [ 5.000,  6.250) = 864 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     13.761 ms/op
     p(99.9990) =     14.423 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.009 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.559 ms/op
                 listUser·p0.999:  9.029 ms/op
                 listUser·p0.9999: 10.774 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.884 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.031 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320106
  mean =      2.997 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 94682 
    [ 2.500,  3.750) = 186902 
    [ 3.750,  5.000) = 31547 
    [ 5.000,  6.250) = 5495 
    [ 6.250,  7.500) = 670 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 293 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.304 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     12.380 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.497 ± 1.781  ops/ms
ClientPb.existUser                       thrpt       3  13.238 ± 1.233  ops/ms
ClientPb.getUser                         thrpt       3  12.943 ± 3.203  ops/ms
ClientPb.listUser                        thrpt       3  10.784 ± 0.135  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.255   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.216   ms/op
ClientPb.getUser                          avgt       3   2.475 ± 0.300   ms/op
ClientPb.listUser                         avgt       3   2.984 ± 0.177   ms/op
ClientPb.createUser                     sample  374672   2.559 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.845           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.798           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.137           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.116           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.498           ms/op
ClientPb.existUser                      sample  384661   2.493 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.737           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.467           ms/op
ClientPb.getUser                        sample  370771   2.587 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.847           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.605           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.535           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.761           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  320106   2.997 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.889           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.304           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.517           ms/op
