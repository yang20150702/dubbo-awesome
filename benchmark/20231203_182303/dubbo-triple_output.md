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
# Warmup Iteration   1: 4.423 ops/ms
# Warmup Iteration   2: 11.759 ops/ms
# Warmup Iteration   3: 12.020 ops/ms
Iteration   1: 12.306 ops/ms
Iteration   2: 12.225 ops/ms
Iteration   3: 12.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.261 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (12.225, 12.261, 12.306), stdev = 0.041
  CI (99.9%): [11.511, 13.012] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.849 ops/ms
# Warmup Iteration   2: 12.678 ops/ms
# Warmup Iteration   3: 12.695 ops/ms
Iteration   1: 12.812 ops/ms
Iteration   2: 12.717 ops/ms
Iteration   3: 12.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.788 ±(99.9%) 1.131 ops/ms [Average]
  (min, avg, max) = (12.717, 12.788, 12.834), stdev = 0.062
  CI (99.9%): [11.657, 13.919] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.552 ops/ms
# Warmup Iteration   2: 12.118 ops/ms
# Warmup Iteration   3: 12.436 ops/ms
Iteration   1: 12.554 ops/ms
Iteration   2: 12.834 ops/ms
Iteration   3: 12.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.712 ±(99.9%) 2.617 ops/ms [Average]
  (min, avg, max) = (12.554, 12.712, 12.834), stdev = 0.143
  CI (99.9%): [10.095, 15.329] (assumes normal distribution)


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
# Warmup Iteration   1: 6.498 ops/ms
# Warmup Iteration   2: 10.353 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.282 ops/ms
Iteration   2: 10.437 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.415 ±(99.9%) 2.256 ops/ms [Average]
  (min, avg, max) = (10.282, 10.415, 10.526), stdev = 0.124
  CI (99.9%): [8.159, 12.671] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.004 ms/op
Iteration   2: 2.570 ±(99.9%) 0.003 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.531, 2.557, 2.570), stdev = 0.022
  CI (99.9%): [2.152, 2.962] (assumes normal distribution)


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.003 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.489 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.480, 2.489, 2.507), stdev = 0.015
  CI (99.9%): [2.218, 2.761] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.538 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.534, 2.538, 2.544), stdev = 0.005
  CI (99.9%): [2.439, 2.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.005 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
Iteration   3: 3.041 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (3.041, 3.044, 3.048), stdev = 0.004
  CI (99.9%): [2.978, 3.110] (assumes normal distribution)


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.728 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.596 ±(99.9%) 0.006 ms/op
Iteration   1: 2.583 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  11.193 ms/op
                 createUser·p0.9999: 14.078 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.574 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  5.551 ms/op
                 createUser·p0.9999: 12.780 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   3: 2.586 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  6.098 ms/op
                 createUser·p0.9999: 11.578 ms/op
                 createUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371647
  mean =      2.581 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 176312 
    [ 2.500,  3.750) = 191082 
    [ 3.750,  5.000) = 3417 
    [ 5.000,  6.250) = 462 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      5.997 ms/op
     p(99.9900) =     13.842 ms/op
     p(99.9990) =     14.788 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  11.066 ms/op
                 existUser·p0.9999: 13.723 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.920 ms/op
                 existUser·p0.9999: 12.816 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  8.878 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381659
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 185812 
    [ 2.500,  3.750) = 192276 
    [ 3.750,  5.000) = 2749 
    [ 5.000,  6.250) = 353 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     12.908 ms/op
     p(99.9990) =     14.099 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  11.265 ms/op
                 getUser·p0.9999: 14.209 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  9.987 ms/op
                 getUser·p0.9999: 14.725 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.197 ms/op
                 getUser·p0.9999: 11.746 ms/op
                 getUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379157
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 184149 
    [ 2.500,  3.750) = 189812 
    [ 3.750,  5.000) = 4153 
    [ 5.000,  6.250) = 503 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.662 ms/op
     p(99.9900) =     13.931 ms/op
     p(99.9990) =     15.060 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.803 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.993 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.553 ms/op
                 listUser·p0.9999: 11.505 ms/op
                 listUser·p1.00:   13.976 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.788 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.856 ms/op
                 listUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313303
  mean =      3.061 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 84006 
    [ 2.500,  3.750) = 187470 
    [ 3.750,  5.000) = 33514 
    [ 5.000,  6.250) = 6615 
    [ 6.250,  7.500) = 843 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 311 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     11.529 ms/op
     p(99.9990) =     13.826 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.261 ± 0.750  ops/ms
ClientPb.existUser                       thrpt       3  12.788 ± 1.131  ops/ms
ClientPb.getUser                         thrpt       3  12.712 ± 2.617  ops/ms
ClientPb.listUser                        thrpt       3  10.415 ± 2.256  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.405   ms/op
ClientPb.existUser                        avgt       3   2.489 ± 0.272   ms/op
ClientPb.getUser                          avgt       3   2.538 ± 0.099   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.066   ms/op
ClientPb.createUser                     sample  371647   2.581 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.950           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           5.997           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.842           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  381659   2.513 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.869           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.143           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.908           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  379157   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.931           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.662           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.931           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  313303   3.061 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.866           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.529           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.976           ms/op
