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
# Warmup Iteration   1: 4.728 ops/ms
# Warmup Iteration   2: 12.331 ops/ms
# Warmup Iteration   3: 12.706 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 12.923 ops/ms
Iteration   3: 13.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.021 ±(99.9%) 2.246 ops/ms [Average]
  (min, avg, max) = (12.923, 13.021, 13.159), stdev = 0.123
  CI (99.9%): [10.775, 15.266] (assumes normal distribution)


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
# Warmup Iteration   1: 8.489 ops/ms
# Warmup Iteration   2: 13.367 ops/ms
# Warmup Iteration   3: 13.312 ops/ms
Iteration   1: 13.368 ops/ms
Iteration   2: 13.170 ops/ms
Iteration   3: 13.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.327 ±(99.9%) 2.591 ops/ms [Average]
  (min, avg, max) = (13.170, 13.327, 13.445), stdev = 0.142
  CI (99.9%): [10.736, 15.919] (assumes normal distribution)


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
# Warmup Iteration   1: 7.655 ops/ms
# Warmup Iteration   2: 12.687 ops/ms
# Warmup Iteration   3: 12.741 ops/ms
Iteration   1: 13.001 ops/ms
Iteration   2: 12.750 ops/ms
Iteration   3: 12.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.896 ±(99.9%) 2.368 ops/ms [Average]
  (min, avg, max) = (12.750, 12.896, 13.001), stdev = 0.130
  CI (99.9%): [10.527, 15.264] (assumes normal distribution)


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
# Warmup Iteration   1: 6.930 ops/ms
# Warmup Iteration   2: 10.822 ops/ms
# Warmup Iteration   3: 10.833 ops/ms
Iteration   1: 10.889 ops/ms
Iteration   2: 10.879 ops/ms
Iteration   3: 10.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.866 ±(99.9%) 0.597 ops/ms [Average]
  (min, avg, max) = (10.828, 10.866, 10.889), stdev = 0.033
  CI (99.9%): [10.269, 11.463] (assumes normal distribution)


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.492, 2.499, 2.510), stdev = 0.009
  CI (99.9%): [2.326, 2.671] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.366 ±(99.9%) 0.002 ms/op
Iteration   1: 2.388 ±(99.9%) 0.004 ms/op
Iteration   2: 2.374 ±(99.9%) 0.004 ms/op
Iteration   3: 2.380 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.381 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.374, 2.381, 2.388), stdev = 0.007
  CI (99.9%): [2.249, 2.512] (assumes normal distribution)


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.004 ms/op
Iteration   1: 2.418 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.425 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (2.418, 2.425, 2.431), stdev = 0.006
  CI (99.9%): [2.309, 2.541] (assumes normal distribution)


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
# Warmup Iteration   1: 4.592 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.004 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
Iteration   3: 2.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.956, 2.960, 2.965), stdev = 0.005
  CI (99.9%): [2.874, 3.046] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  11.233 ms/op
                 createUser·p0.9999: 14.057 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.735 ms/op
                 createUser·p0.999:  9.217 ms/op
                 createUser·p0.9999: 12.621 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.599 ms/op
                 createUser·p0.9999: 12.153 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380197
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 183949 
    [ 2.500,  3.750) = 191208 
    [ 3.750,  5.000) = 3824 
    [ 5.000,  6.250) = 717 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.641 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.542 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.726 ms/op
                 existUser·p0.9999: 14.559 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 2.396 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  6.279 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  5.392 ms/op
                 existUser·p0.9999: 12.578 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398491
  mean =      2.407 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 205762 
    [ 2.500,  3.750) = 189575 
    [ 3.750,  5.000) = 2495 
    [ 5.000,  6.250) = 216 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      5.739 ms/op
     p(99.9900) =     13.653 ms/op
     p(99.9990) =     15.271 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.001 ms/op
                 getUser·p0.9999: 14.385 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.103 ms/op
                 getUser·p0.999:  7.714 ms/op
                 getUser·p0.9999: 14.621 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.918 ms/op
                 getUser·p0.9999: 11.700 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388163
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 194756 
    [ 2.500,  3.750) = 187384 
    [ 3.750,  5.000) = 4709 
    [ 5.000,  6.250) = 771 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.048 ms/op
     p(99.9000) =      6.502 ms/op
     p(99.9900) =     14.102 ms/op
     p(99.9990) =     14.946 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
Iteration   1: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 10.014 ms/op
                 listUser·p1.00:   10.928 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.686 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   12.026 ms/op

Iteration   3: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.807 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  8.879 ms/op
                 listUser·p0.9999: 10.325 ms/op
                 listUser·p1.00:   10.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323886
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 99932 
    [ 2.500,  3.750) = 187445 
    [ 3.750,  5.000) = 30079 
    [ 5.000,  6.250) = 5067 
    [ 6.250,  7.500) = 571 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 336 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     10.519 ms/op
     p(99.9990) =     11.196 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.021 ± 2.246  ops/ms
ClientPb.existUser                       thrpt       3  13.327 ± 2.591  ops/ms
ClientPb.getUser                         thrpt       3  12.896 ± 2.368  ops/ms
ClientPb.listUser                        thrpt       3  10.866 ± 0.597  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.173   ms/op
ClientPb.existUser                        avgt       3   2.381 ± 0.131   ms/op
ClientPb.getUser                          avgt       3   2.425 ± 0.116   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.086   ms/op
ClientPb.createUser                     sample  380197   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.595           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.641           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  398491   2.407 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.932           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.739           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.653           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.417           ms/op
ClientPb.getUser                        sample  388163   2.471 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.829           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.048           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.502           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.102           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.581           ms/op
ClientPb.listUser                       sample  323886   2.961 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.995           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.519           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.026           ms/op
