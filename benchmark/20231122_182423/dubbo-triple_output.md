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
# Warmup Iteration   1: 4.908 ops/ms
# Warmup Iteration   2: 12.167 ops/ms
# Warmup Iteration   3: 12.584 ops/ms
Iteration   1: 12.656 ops/ms
Iteration   2: 12.707 ops/ms
Iteration   3: 12.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.688 ±(99.9%) 0.500 ops/ms [Average]
  (min, avg, max) = (12.656, 12.688, 12.707), stdev = 0.027
  CI (99.9%): [12.188, 13.188] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.505 ops/ms
# Warmup Iteration   2: 13.232 ops/ms
# Warmup Iteration   3: 12.876 ops/ms
Iteration   1: 12.967 ops/ms
Iteration   2: 12.931 ops/ms
Iteration   3: 13.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.049 ±(99.9%) 3.171 ops/ms [Average]
  (min, avg, max) = (12.931, 13.049, 13.249), stdev = 0.174
  CI (99.9%): [9.878, 16.220] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.346 ops/ms
# Warmup Iteration   2: 12.654 ops/ms
# Warmup Iteration   3: 12.865 ops/ms
Iteration   1: 12.855 ops/ms
Iteration   2: 12.992 ops/ms
Iteration   3: 12.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.927 ±(99.9%) 1.250 ops/ms [Average]
  (min, avg, max) = (12.855, 12.927, 12.992), stdev = 0.069
  CI (99.9%): [11.678, 14.177] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.557 ops/ms
# Warmup Iteration   2: 10.208 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.423 ±(99.9%) 1.183 ops/ms [Average]
  (min, avg, max) = (10.378, 10.423, 10.497), stdev = 0.065
  CI (99.9%): [9.239, 11.606] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.580 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (2.534, 2.565, 2.580), stdev = 0.026
  CI (99.9%): [2.085, 3.045] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.455, 2.474, 2.490), stdev = 0.017
  CI (99.9%): [2.154, 2.793] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.003 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.469, 2.485, 2.496), stdev = 0.014
  CI (99.9%): [2.222, 2.748] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.005 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
Iteration   2: 3.068 ±(99.9%) 0.005 ms/op
Iteration   3: 3.024 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.024, 3.055, 3.072), stdev = 0.026
  CI (99.9%): [2.573, 3.536] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.354 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.712 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  12.181 ms/op
                 createUser·p0.9999: 14.746 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.885 ms/op
                 createUser·p0.9999: 12.771 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  9.184 ms/op
                 createUser·p0.9999: 11.438 ms/op
                 createUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376184
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 179235 
    [ 2.500,  3.750) = 192306 
    [ 3.750,  5.000) = 3575 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      9.254 ms/op
     p(99.9900) =     13.867 ms/op
     p(99.9990) =     14.815 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  10.032 ms/op
                 existUser·p0.9999: 14.817 ms/op
                 existUser·p1.00:   15.581 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  5.495 ms/op
                 existUser·p0.9999: 12.027 ms/op
                 existUser·p1.00:   12.222 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  8.508 ms/op
                 existUser·p0.9999: 14.002 ms/op
                 existUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386694
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 190773 
    [ 2.500,  3.750) = 192370 
    [ 3.750,  5.000) = 2641 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      6.283 ms/op
     p(99.9900) =     14.139 ms/op
     p(99.9990) =     15.422 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.314 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  12.855 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  10.192 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  7.534 ms/op
                 getUser·p0.9999: 11.324 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381903
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188029 
    [ 2.500,  5.000) = 192278 
    [ 5.000,  7.500) = 1208 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      8.882 ms/op
     p(99.9900) =     14.434 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.708 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.009 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  8.855 ms/op
                 listUser·p0.9999: 11.068 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.734 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  10.273 ms/op
                 listUser·p0.9999: 13.074 ms/op
                 listUser·p1.00:   14.123 ms/op

Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.927 ms/op
                 listUser·p0.9999: 12.595 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312984
  mean =      3.065 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 83057 
    [ 2.500,  3.750) = 187051 
    [ 3.750,  5.000) = 34172 
    [ 5.000,  6.250) = 7019 
    [ 6.250,  7.500) = 881 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 198 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     12.491 ms/op
     p(99.9990) =     13.513 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.688 ± 0.500  ops/ms
ClientPb.existUser                       thrpt       3  13.049 ± 3.171  ops/ms
ClientPb.getUser                         thrpt       3  12.927 ± 1.250  ops/ms
ClientPb.listUser                        thrpt       3  10.423 ± 1.183  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.480   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.319   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.263   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.481   ms/op
ClientPb.createUser                     sample  376184   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.867           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.466           ms/op
ClientPb.existUser                      sample  386694   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.283           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.139           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.581           ms/op
ClientPb.getUser                        sample  381903   2.511 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.710           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.882           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.434           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.856           ms/op
ClientPb.listUser                       sample  312984   3.065 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.734           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.491           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.123           ms/op
