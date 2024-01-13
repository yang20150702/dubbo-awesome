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
# Warmup Iteration   1: 4.330 ops/ms
# Warmup Iteration   2: 12.085 ops/ms
# Warmup Iteration   3: 12.406 ops/ms
Iteration   1: 12.652 ops/ms
Iteration   2: 12.807 ops/ms
Iteration   3: 12.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.777 ±(99.9%) 2.050 ops/ms [Average]
  (min, avg, max) = (12.652, 12.777, 12.870), stdev = 0.112
  CI (99.9%): [10.726, 14.827] (assumes normal distribution)


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
# Warmup Iteration   1: 8.086 ops/ms
# Warmup Iteration   2: 13.074 ops/ms
# Warmup Iteration   3: 13.266 ops/ms
Iteration   1: 13.155 ops/ms
Iteration   2: 13.039 ops/ms
Iteration   3: 13.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.100 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (13.039, 13.100, 13.155), stdev = 0.058
  CI (99.9%): [12.038, 14.161] (assumes normal distribution)


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
# Warmup Iteration   1: 7.892 ops/ms
# Warmup Iteration   2: 12.482 ops/ms
# Warmup Iteration   3: 12.867 ops/ms
Iteration   1: 12.945 ops/ms
Iteration   2: 12.968 ops/ms
Iteration   3: 13.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.994 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (12.945, 12.994, 13.068), stdev = 0.065
  CI (99.9%): [11.808, 14.180] (assumes normal distribution)


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
# Warmup Iteration   1: 6.805 ops/ms
# Warmup Iteration   2: 10.521 ops/ms
# Warmup Iteration   3: 10.692 ops/ms
Iteration   1: 10.722 ops/ms
Iteration   2: 10.767 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.751 ±(99.9%) 0.457 ops/ms [Average]
  (min, avg, max) = (10.722, 10.751, 10.767), stdev = 0.025
  CI (99.9%): [10.294, 11.208] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.472 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (2.455, 2.472, 2.497), stdev = 0.023
  CI (99.9%): [2.059, 2.885] (assumes normal distribution)


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.455, 2.460, 2.466), stdev = 0.006
  CI (99.9%): [2.357, 2.563] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.003 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.490, 2.501, 2.513), stdev = 0.012
  CI (99.9%): [2.285, 2.717] (assumes normal distribution)


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
Iteration   3: 3.024 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (3.017, 3.022, 3.024), stdev = 0.004
  CI (99.9%): [2.943, 3.100] (assumes normal distribution)


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  11.804 ms/op
                 createUser·p0.9999: 14.061 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  9.393 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.892 ms/op
                 createUser·p0.9999: 11.855 ms/op
                 createUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381801
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 183004 
    [ 2.500,  3.750) = 195189 
    [ 3.750,  5.000) = 2811 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.919 ms/op
     p(99.9900) =     13.497 ms/op
     p(99.9990) =     14.306 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  5.485 ms/op
                 existUser·p0.9999: 13.839 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.392 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  6.548 ms/op
                 existUser·p0.9999: 14.160 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 12.070 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399739
  mean =      2.399 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 203141 
    [ 2.500,  3.750) = 193865 
    [ 3.750,  5.000) = 1960 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.006 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  5.815 ms/op
                 getUser·p0.9999: 14.709 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  7.871 ms/op
                 getUser·p0.9999: 12.423 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.709 ms/op
                 getUser·p0.999:  6.836 ms/op
                 getUser·p0.9999: 10.813 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388080
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 194231 
    [ 2.500,  3.750) = 188385 
    [ 3.750,  5.000) = 3843 
    [ 5.000,  6.250) = 1073 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      6.978 ms/op
     p(99.9900) =     13.326 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 4.921 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.009 ms/op
Iteration   1: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.918 ms/op
                 listUser·p0.9999: 10.342 ms/op
                 listUser·p1.00:   10.781 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.494 ms/op
                 listUser·p0.9999: 11.063 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   3: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  10.552 ms/op
                 listUser·p0.9999: 14.324 ms/op
                 listUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323198
  mean =      2.968 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 101441 
    [ 2.500,  3.750) = 184839 
    [ 3.750,  5.000) = 29539 
    [ 5.000,  6.250) = 6043 
    [ 6.250,  7.500) = 514 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     13.725 ms/op
     p(99.9990) =     14.861 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.777 ± 2.050  ops/ms
ClientPb.existUser                       thrpt       3  13.100 ± 1.062  ops/ms
ClientPb.getUser                         thrpt       3  12.994 ± 1.186  ops/ms
ClientPb.listUser                        thrpt       3  10.751 ± 0.457  ops/ms
ClientPb.createUser                       avgt       3   2.472 ± 0.413   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.103   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.216   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 0.078   ms/op
ClientPb.createUser                     sample  381801   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.783           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.919           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.497           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  399739   2.399 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.823           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.864           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.828           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.286           ms/op
ClientPb.getUser                        sample  388080   2.472 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.978           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.326           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.270           ms/op
ClientPb.listUser                       sample  323198   2.968 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.740           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.725           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.106           ms/op
