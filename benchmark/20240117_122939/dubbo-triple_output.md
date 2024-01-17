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
# Warmup Iteration   1: 5.081 ops/ms
# Warmup Iteration   2: 12.105 ops/ms
# Warmup Iteration   3: 12.333 ops/ms
Iteration   1: 12.476 ops/ms
Iteration   2: 12.581 ops/ms
Iteration   3: 12.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.585 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (12.476, 12.585, 12.697), stdev = 0.110
  CI (99.9%): [10.572, 14.598] (assumes normal distribution)


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
# Warmup Iteration   1: 8.097 ops/ms
# Warmup Iteration   2: 13.197 ops/ms
# Warmup Iteration   3: 13.228 ops/ms
Iteration   1: 13.334 ops/ms
Iteration   2: 13.195 ops/ms
Iteration   3: 13.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.300 ±(99.9%) 1.682 ops/ms [Average]
  (min, avg, max) = (13.195, 13.300, 13.370), stdev = 0.092
  CI (99.9%): [11.617, 14.982] (assumes normal distribution)


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
# Warmup Iteration   1: 8.149 ops/ms
# Warmup Iteration   2: 12.786 ops/ms
# Warmup Iteration   3: 13.003 ops/ms
Iteration   1: 12.912 ops/ms
Iteration   2: 12.673 ops/ms
Iteration   3: 12.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.852 ±(99.9%) 2.878 ops/ms [Average]
  (min, avg, max) = (12.673, 12.852, 12.971), stdev = 0.158
  CI (99.9%): [9.974, 15.730] (assumes normal distribution)


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
# Warmup Iteration   1: 6.542 ops/ms
# Warmup Iteration   2: 10.463 ops/ms
# Warmup Iteration   3: 10.707 ops/ms
Iteration   1: 10.801 ops/ms
Iteration   2: 10.771 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.759 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (10.706, 10.759, 10.801), stdev = 0.048
  CI (99.9%): [9.878, 11.641] (assumes normal distribution)


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.497, 2.512, 2.529), stdev = 0.016
  CI (99.9%): [2.217, 2.806] (assumes normal distribution)


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.003 ms/op
Iteration   1: 2.432 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.003 ms/op
Iteration   3: 2.419 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.419, 2.431, 2.441), stdev = 0.011
  CI (99.9%): [2.235, 2.627] (assumes normal distribution)


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.003 ms/op
Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.449, 2.461, 2.469), stdev = 0.010
  CI (99.9%): [2.272, 2.649] (assumes normal distribution)


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.004 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
Iteration   2: 2.952 ±(99.9%) 0.005 ms/op
Iteration   3: 2.953 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.025 ms/op [Average]
  (min, avg, max) = (2.950, 2.951, 2.953), stdev = 0.001
  CI (99.9%): [2.927, 2.976] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  6.319 ms/op
                 createUser·p0.9999: 13.500 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.069 ms/op
                 createUser·p0.9999: 12.351 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  8.300 ms/op
                 createUser·p0.9999: 11.738 ms/op
                 createUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384734
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 186220 
    [ 2.500,  3.750) = 194595 
    [ 3.750,  5.000) = 3035 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.292 ms/op
     p(99.9900) =     12.805 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


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
# Warmup Iteration   1: 3.667 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  6.006 ms/op
                 existUser·p0.9999: 13.182 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  7.281 ms/op
                 existUser·p0.9999: 12.516 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.796 ms/op
                 existUser·p0.999:  8.334 ms/op
                 existUser·p0.9999: 12.126 ms/op
                 existUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391384
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 194484 
    [ 2.500,  3.750) = 193724 
    [ 3.750,  5.000) = 2206 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      7.443 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     13.290 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.006 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.373 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.651 ms/op
                 getUser·p0.999:  5.545 ms/op
                 getUser·p0.9999: 14.352 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.677 ms/op
                 getUser·p0.999:  8.811 ms/op
                 getUser·p0.9999: 13.077 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  5.909 ms/op
                 getUser·p0.9999: 11.829 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389445
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 196539 
    [ 2.500,  3.750) = 187700 
    [ 3.750,  5.000) = 3818 
    [ 5.000,  6.250) = 836 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      7.502 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.998 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 4.648 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
Iteration   1: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.804 ms/op
                 listUser·p0.9999: 10.852 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   2: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.105 ms/op
                 listUser·p0.9999: 10.445 ms/op
                 listUser·p1.00:   10.846 ms/op

Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.918 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323931
  mean =      2.961 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 103847 
    [ 2.500,  3.750) = 183495 
    [ 3.750,  5.000) = 29659 
    [ 5.000,  6.250) = 5558 
    [ 6.250,  7.500) = 573 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     10.797 ms/op
     p(99.9990) =     11.576 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.585 ± 2.013  ops/ms
ClientPb.existUser                       thrpt       3  13.300 ± 1.682  ops/ms
ClientPb.getUser                         thrpt       3  12.852 ± 2.878  ops/ms
ClientPb.listUser                        thrpt       3  10.759 ± 0.882  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.294   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.196   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.189   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.025   ms/op
ClientPb.createUser                     sample  384734   2.493 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.804           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.292           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.805           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.648           ms/op
ClientPb.existUser                      sample  391384   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.685           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.443           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.960           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.369           ms/op
ClientPb.getUser                        sample  389445   2.463 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.373           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.502           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.073           ms/op
ClientPb.listUser                       sample  323931   2.961 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.701           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.797           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.682           ms/op
