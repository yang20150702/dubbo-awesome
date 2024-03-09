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
# Warmup Iteration   1: 4.753 ops/ms
# Warmup Iteration   2: 12.246 ops/ms
# Warmup Iteration   3: 12.608 ops/ms
Iteration   1: 12.791 ops/ms
Iteration   2: 12.853 ops/ms
Iteration   3: 12.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.802 ±(99.9%) 0.857 ops/ms [Average]
  (min, avg, max) = (12.761, 12.802, 12.853), stdev = 0.047
  CI (99.9%): [11.944, 13.659] (assumes normal distribution)


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
# Warmup Iteration   1: 8.835 ops/ms
# Warmup Iteration   2: 13.328 ops/ms
# Warmup Iteration   3: 13.413 ops/ms
Iteration   1: 13.373 ops/ms
Iteration   2: 13.380 ops/ms
Iteration   3: 13.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.389 ±(99.9%) 0.385 ops/ms [Average]
  (min, avg, max) = (13.373, 13.389, 13.413), stdev = 0.021
  CI (99.9%): [13.004, 13.773] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.980 ops/ms
# Warmup Iteration   2: 12.517 ops/ms
# Warmup Iteration   3: 12.673 ops/ms
Iteration   1: 13.125 ops/ms
Iteration   2: 12.890 ops/ms
Iteration   3: 13.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.052 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (12.890, 13.052, 13.142), stdev = 0.141
  CI (99.9%): [10.482, 15.622] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.779 ops/ms
# Warmup Iteration   2: 10.593 ops/ms
# Warmup Iteration   3: 10.781 ops/ms
Iteration   1: 10.831 ops/ms
Iteration   2: 10.780 ops/ms
Iteration   3: 10.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.789 ±(99.9%) 0.712 ops/ms [Average]
  (min, avg, max) = (10.754, 10.789, 10.831), stdev = 0.039
  CI (99.9%): [10.077, 11.500] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.003 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.464 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.454, 2.464, 2.480), stdev = 0.014
  CI (99.9%): [2.215, 2.713] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.403 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.004 ms/op
Iteration   1: 2.392 ±(99.9%) 0.005 ms/op
Iteration   2: 2.399 ±(99.9%) 0.003 ms/op
Iteration   3: 2.381 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.391 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.381, 2.391, 2.399), stdev = 0.009
  CI (99.9%): [2.228, 2.554] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.460, 2.464, 2.469), stdev = 0.005
  CI (99.9%): [2.377, 2.551] (assumes normal distribution)


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
Iteration   2: 2.937 ±(99.9%) 0.005 ms/op
Iteration   3: 2.981 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.959 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.937, 2.959, 2.981), stdev = 0.022
  CI (99.9%): [2.556, 3.361] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.832 ms/op
                 createUser·p0.999:  7.860 ms/op
                 createUser·p0.9999: 13.848 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  7.724 ms/op
                 createUser·p0.9999: 12.389 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  7.706 ms/op
                 createUser·p0.9999: 10.896 ms/op
                 createUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387830
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 193837 
    [ 2.500,  3.750) = 189819 
    [ 3.750,  5.000) = 3242 
    [ 5.000,  6.250) = 414 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      7.679 ms/op
     p(99.9900) =     13.537 ms/op
     p(99.9990) =     14.162 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  8.094 ms/op
                 existUser·p0.9999: 13.405 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  7.619 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  7.229 ms/op
                 existUser·p0.9999: 11.759 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398248
  mean =      2.408 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 202278 
    [ 2.500,  3.750) = 192559 
    [ 3.750,  5.000) = 2471 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.328 ms/op
     p(99.9900) =     12.700 ms/op
     p(99.9990) =     13.862 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  6.280 ms/op
                 getUser·p0.9999: 13.578 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 12.491 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  5.423 ms/op
                 getUser·p0.9999: 11.305 ms/op
                 getUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387209
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 194355 
    [ 2.500,  3.750) = 187407 
    [ 3.750,  5.000) = 4328 
    [ 5.000,  6.250) = 615 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      7.263 ms/op
     p(99.9900) =     13.095 ms/op
     p(99.9990) =     13.920 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
Iteration   1: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.759 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.581 ms/op
                 listUser·p0.9999: 10.633 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  10.191 ms/op
                 listUser·p0.9999: 11.907 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 11.583 ms/op
                 listUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323704
  mean =      2.963 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 98949 
    [ 2.500,  3.750) = 188653 
    [ 3.750,  5.000) = 29398 
    [ 5.000,  6.250) = 5376 
    [ 6.250,  7.500) = 511 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 168 
    [10.000, 11.250) = 227 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.753 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     12.670 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.802 ± 0.857  ops/ms
ClientPb.existUser                       thrpt       3  13.389 ± 0.385  ops/ms
ClientPb.getUser                         thrpt       3  13.052 ± 2.570  ops/ms
ClientPb.listUser                        thrpt       3  10.789 ± 0.712  ops/ms
ClientPb.createUser                       avgt       3   2.464 ± 0.249   ms/op
ClientPb.existUser                        avgt       3   2.391 ± 0.163   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.087   ms/op
ClientPb.listUser                         avgt       3   2.959 ± 0.402   ms/op
ClientPb.createUser                     sample  387830   2.473 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.689           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.499           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.679           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.537           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.631           ms/op
ClientPb.existUser                      sample  398248   2.408 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.904           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.328           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.700           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  387209   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.588           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.263           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.095           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  323704   2.963 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.759           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.753           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.206           ms/op
