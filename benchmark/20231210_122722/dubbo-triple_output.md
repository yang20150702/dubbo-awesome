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
# Warmup Iteration   1: 5.123 ops/ms
# Warmup Iteration   2: 11.734 ops/ms
# Warmup Iteration   3: 12.019 ops/ms
Iteration   1: 12.171 ops/ms
Iteration   2: 12.150 ops/ms
Iteration   3: 12.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.176 ±(99.9%) 0.513 ops/ms [Average]
  (min, avg, max) = (12.150, 12.176, 12.206), stdev = 0.028
  CI (99.9%): [11.663, 12.689] (assumes normal distribution)


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
# Warmup Iteration   1: 8.112 ops/ms
# Warmup Iteration   2: 12.806 ops/ms
# Warmup Iteration   3: 12.805 ops/ms
Iteration   1: 12.777 ops/ms
Iteration   2: 12.832 ops/ms
Iteration   3: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.805 ±(99.9%) 0.507 ops/ms [Average]
  (min, avg, max) = (12.777, 12.805, 12.832), stdev = 0.028
  CI (99.9%): [12.298, 13.311] (assumes normal distribution)


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
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 12.114 ops/ms
# Warmup Iteration   3: 12.456 ops/ms
Iteration   1: 12.293 ops/ms
Iteration   2: 12.420 ops/ms
Iteration   3: 12.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.369 ±(99.9%) 1.225 ops/ms [Average]
  (min, avg, max) = (12.293, 12.369, 12.420), stdev = 0.067
  CI (99.9%): [11.144, 13.594] (assumes normal distribution)


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
# Warmup Iteration   1: 6.311 ops/ms
# Warmup Iteration   2: 10.332 ops/ms
# Warmup Iteration   3: 10.413 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.478 ±(99.9%) 0.157 ops/ms [Average]
  (min, avg, max) = (10.471, 10.478, 10.487), stdev = 0.009
  CI (99.9%): [10.321, 10.635] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.004 ms/op
Iteration   1: 2.596 ±(99.9%) 0.004 ms/op
Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
Iteration   3: 2.580 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.597 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (2.580, 2.597, 2.616), stdev = 0.018
  CI (99.9%): [2.261, 2.934] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.532 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.511, 2.532, 2.545), stdev = 0.018
  CI (99.9%): [2.199, 2.865] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.003 ms/op
Iteration   1: 2.522 ±(99.9%) 0.003 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.515, 2.522, 2.530), stdev = 0.008
  CI (99.9%): [2.385, 2.660] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.884 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
Iteration   3: 3.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.023, 3.034, 3.046), stdev = 0.011
  CI (99.9%): [2.824, 3.243] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.104 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
Iteration   1: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  11.846 ms/op
                 createUser·p0.9999: 14.591 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 13.712 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  8.999 ms/op
                 createUser·p0.9999: 11.210 ms/op
                 createUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372226
  mean =      2.576 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 177315 
    [ 2.500,  3.750) = 190391 
    [ 3.750,  5.000) = 3396 
    [ 5.000,  6.250) = 622 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     13.726 ms/op
     p(99.9990) =     15.349 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  7.446 ms/op
                 existUser·p0.9999: 14.210 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.599 ms/op
                 existUser·p0.999:  8.278 ms/op
                 existUser·p0.9999: 12.915 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.026 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  5.128 ms/op
                 existUser·p0.9999: 12.231 ms/op
                 existUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386801
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193689 
    [ 2.500,  5.000) = 192452 
    [ 5.000,  7.500) = 306 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.013 ms/op
     p(99.9900) =     13.719 ms/op
     p(99.9990) =     14.752 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  11.799 ms/op
                 getUser·p0.9999: 14.320 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  9.594 ms/op
                 getUser·p0.9999: 13.823 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  8.469 ms/op
                 getUser·p0.9999: 11.392 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375389
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 182771 
    [ 2.500,  3.750) = 187208 
    [ 3.750,  5.000) = 4120 
    [ 5.000,  6.250) = 740 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.576 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.870 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.009 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 13.133 ms/op
                 listUser·p1.00:   14.483 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 12.325 ms/op
                 listUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314691
  mean =      3.047 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 86197 
    [ 2.500,  3.750) = 186566 
    [ 3.750,  5.000) = 34301 
    [ 5.000,  6.250) = 6072 
    [ 6.250,  7.500) = 762 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 324 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     12.435 ms/op
     p(99.9990) =     14.392 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.176 ± 0.513  ops/ms
ClientPb.existUser                       thrpt       3  12.805 ± 0.507  ops/ms
ClientPb.getUser                         thrpt       3  12.369 ± 1.225  ops/ms
ClientPb.listUser                        thrpt       3  10.478 ± 0.157  ops/ms
ClientPb.createUser                       avgt       3   2.597 ± 0.337   ms/op
ClientPb.existUser                        avgt       3   2.532 ± 0.333   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.138   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.209   ms/op
ClientPb.createUser                     sample  372226   2.576 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.848           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.126           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.726           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.401           ms/op
ClientPb.existUser                      sample  386801   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.719           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.120           ms/op
ClientPb.getUser                        sample  375389   2.555 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.566           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.716           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.909           ms/op
ClientPb.listUser                       sample  314691   3.047 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.770           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.483           ms/op
