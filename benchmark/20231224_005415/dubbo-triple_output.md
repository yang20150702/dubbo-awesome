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
# Warmup Iteration   1: 4.869 ops/ms
# Warmup Iteration   2: 12.025 ops/ms
# Warmup Iteration   3: 12.108 ops/ms
Iteration   1: 12.442 ops/ms
Iteration   2: 12.558 ops/ms
Iteration   3: 12.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.565 ±(99.9%) 2.294 ops/ms [Average]
  (min, avg, max) = (12.442, 12.565, 12.694), stdev = 0.126
  CI (99.9%): [10.271, 14.859] (assumes normal distribution)


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
# Warmup Iteration   1: 8.024 ops/ms
# Warmup Iteration   2: 12.859 ops/ms
# Warmup Iteration   3: 12.604 ops/ms
Iteration   1: 12.782 ops/ms
Iteration   2: 12.907 ops/ms
Iteration   3: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.902 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (12.782, 12.902, 13.018), stdev = 0.118
  CI (99.9%): [10.750, 15.054] (assumes normal distribution)


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
# Warmup Iteration   1: 7.787 ops/ms
# Warmup Iteration   2: 12.526 ops/ms
# Warmup Iteration   3: 12.720 ops/ms
Iteration   1: 12.873 ops/ms
Iteration   2: 12.706 ops/ms
Iteration   3: 12.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.752 ±(99.9%) 1.937 ops/ms [Average]
  (min, avg, max) = (12.676, 12.752, 12.873), stdev = 0.106
  CI (99.9%): [10.815, 14.688] (assumes normal distribution)


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
# Warmup Iteration   1: 6.721 ops/ms
# Warmup Iteration   2: 10.387 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.625 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.564 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (10.533, 10.564, 10.625), stdev = 0.052
  CI (99.9%): [9.615, 11.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.537 ±(99.9%) 0.003 ms/op
Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.551 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.537, 2.551, 2.575), stdev = 0.021
  CI (99.9%): [2.167, 2.935] (assumes normal distribution)


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
# Warmup Iteration   1: 3.669 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.463 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.454, 2.463, 2.474), stdev = 0.010
  CI (99.9%): [2.278, 2.649] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.003 ms/op
Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.501, 2.513, 2.531), stdev = 0.016
  CI (99.9%): [2.222, 2.804] (assumes normal distribution)


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.005 ms/op
Iteration   1: 3.067 ±(99.9%) 0.005 ms/op
Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
Iteration   3: 3.067 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.069 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (3.067, 3.069, 3.072), stdev = 0.003
  CI (99.9%): [3.021, 3.117] (assumes normal distribution)


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 13.720 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  9.734 ms/op
                 createUser·p0.9999: 12.747 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  8.453 ms/op
                 createUser·p0.9999: 9.689 ms/op
                 createUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378472
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 179652 
    [ 2.500,  3.750) = 194167 
    [ 3.750,  5.000) = 3662 
    [ 5.000,  6.250) = 473 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.545 ms/op
     p(99.9900) =     13.110 ms/op
     p(99.9990) =     14.176 ms/op
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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  7.286 ms/op
                 existUser·p0.9999: 13.374 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  8.495 ms/op
                 existUser·p0.9999: 12.242 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.627 ms/op
                 existUser·p0.999:  8.818 ms/op
                 existUser·p0.9999: 11.663 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384950
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 184839 
    [ 2.500,  3.750) = 196742 
    [ 3.750,  5.000) = 2537 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      7.935 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     14.098 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  5.141 ms/op
                 getUser·p0.9999: 13.748 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  9.307 ms/op
                 getUser·p0.9999: 13.670 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.913 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380729
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 185932 
    [ 2.500,  3.750) = 189185 
    [ 3.750,  5.000) = 4424 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      6.828 ms/op
     p(99.9900) =     13.532 ms/op
     p(99.9990) =     14.391 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.792 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.009 ms/op
Iteration   1: 3.097 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  8.975 ms/op
                 listUser·p0.9999: 10.437 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   3: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.699 ms/op
                 listUser·p1.00:   10.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311093
  mean =      3.083 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 78381 
    [ 2.500,  3.750) = 187882 
    [ 3.750,  5.000) = 37103 
    [ 5.000,  6.250) = 6339 
    [ 6.250,  7.500) = 657 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.538 ms/op
     p(99.9999) =     11.829 ms/op
    p(100.0000) =     11.829 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.565 ± 2.294  ops/ms
ClientPb.existUser                       thrpt       3  12.902 ± 2.152  ops/ms
ClientPb.getUser                         thrpt       3  12.752 ± 1.937  ops/ms
ClientPb.listUser                        thrpt       3  10.564 ± 0.949  ops/ms
ClientPb.createUser                       avgt       3   2.551 ± 0.384   ms/op
ClientPb.existUser                        avgt       3   2.463 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.291   ms/op
ClientPb.listUser                         avgt       3   3.069 ± 0.048   ms/op
ClientPb.createUser                     sample  378472   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.885           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.545           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.110           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  384950   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.726           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.601           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.935           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.993           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  380729   2.519 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.723           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.828           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.532           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  311093   3.083 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.829           ms/op
