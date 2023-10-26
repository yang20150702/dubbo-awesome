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
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 8.978 ops/ms
Iteration   1: 9.781 ops/ms
Iteration   2: 10.118 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.930 ±(99.9%) 3.133 ops/ms [Average]
  (min, avg, max) = (9.781, 9.930, 10.118), stdev = 0.172
  CI (99.9%): [6.797, 13.063] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.244 ops/ms
# Warmup Iteration   2: 9.449 ops/ms
# Warmup Iteration   3: 9.831 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.126 ops/ms
Iteration   3: 10.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.365 ±(99.9%) 4.280 ops/ms [Average]
  (min, avg, max) = (10.126, 10.365, 10.595), stdev = 0.235
  CI (99.9%): [6.085, 14.646] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.324 ops/ms
# Warmup Iteration   2: 9.174 ops/ms
# Warmup Iteration   3: 9.630 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 9.926 ops/ms
Iteration   3: 9.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.934 ±(99.9%) 0.657 ops/ms [Average]
  (min, avg, max) = (9.902, 9.934, 9.973), stdev = 0.036
  CI (99.9%): [9.276, 10.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.286 ops/ms
# Warmup Iteration   2: 7.935 ops/ms
# Warmup Iteration   3: 8.132 ops/ms
Iteration   1: 8.322 ops/ms
Iteration   2: 8.397 ops/ms
Iteration   3: 8.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.367 ±(99.9%) 0.730 ops/ms [Average]
  (min, avg, max) = (8.322, 8.367, 8.397), stdev = 0.040
  CI (99.9%): [7.637, 9.098] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.785 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.004 ms/op
Iteration   1: 3.216 ±(99.9%) 0.003 ms/op
Iteration   2: 3.196 ±(99.9%) 0.003 ms/op
Iteration   3: 3.303 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.238 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (3.196, 3.238, 3.303), stdev = 0.057
  CI (99.9%): [2.198, 4.279] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.091 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.004 ms/op
Iteration   1: 3.125 ±(99.9%) 0.003 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 3.134 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.048, 3.102, 3.134), stdev = 0.047
  CI (99.9%): [2.240, 3.965] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.143 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.002 ms/op
Iteration   1: 3.218 ±(99.9%) 0.002 ms/op
Iteration   2: 3.240 ±(99.9%) 0.003 ms/op
Iteration   3: 3.245 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.234 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.218, 3.234, 3.245), stdev = 0.014
  CI (99.9%): [2.973, 3.496] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.352 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.004 ms/op
Iteration   1: 3.867 ±(99.9%) 0.005 ms/op
Iteration   2: 3.836 ±(99.9%) 0.006 ms/op
Iteration   3: 3.825 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.843 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (3.825, 3.843, 3.867), stdev = 0.022
  CI (99.9%): [3.438, 4.247] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.598 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  19.903 ms/op
                 createUser·p0.9999: 23.371 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.190 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  12.020 ms/op
                 createUser·p0.9999: 19.167 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299574
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17509 
    [ 2.500,  5.000) = 278222 
    [ 5.000,  7.500) = 2798 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.392 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     22.123 ms/op
     p(99.9990) =     23.726 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.076 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
Iteration   1: 3.207 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 18.778 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   2: 3.146 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  14.207 ms/op
                 existUser·p0.9999: 21.922 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  12.626 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301312
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13317 
    [ 2.500,  5.000) = 282224 
    [ 5.000,  7.500) = 4921 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     13.872 ms/op
     p(99.9900) =     21.623 ms/op
     p(99.9990) =     22.740 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.179 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
Iteration   1: 3.285 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  14.227 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  14.410 ms/op
                 getUser·p0.9999: 21.362 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.201 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  13.189 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297353
  mean =      3.226 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8013 
    [ 2.500,  5.000) = 284593 
    [ 5.000,  7.500) = 3814 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     14.029 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     21.828 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.766 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.011 ms/op
Iteration   1: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.578 ms/op
                 listUser·p0.9999: 23.571 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 3.873 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.015 ms/op
                 listUser·p0.9999: 19.660 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 3.877 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.378 ms/op
                 listUser·p0.9999: 16.016 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247397
  mean =      3.879 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 240144 
    [ 5.000,  7.500) = 5649 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 368 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.592 ms/op
     p(99.9900) =     19.931 ms/op
     p(99.9990) =     23.983 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.930 ± 3.133  ops/ms
ClientPb.existUser                       thrpt       3  10.365 ± 4.280  ops/ms
ClientPb.getUser                         thrpt       3   9.934 ± 0.657  ops/ms
ClientPb.listUser                        thrpt       3   8.367 ± 0.730  ops/ms
ClientPb.createUser                       avgt       3   3.238 ± 1.040   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 0.863   ms/op
ClientPb.getUser                          avgt       3   3.234 ± 0.262   ms/op
ClientPb.listUser                         avgt       3   3.843 ± 0.404   ms/op
ClientPb.createUser                     sample  299574   3.204 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.810           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.392           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.318           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.123           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  301312   3.182 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.872           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.623           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.938           ms/op
ClientPb.getUser                        sample  297353   3.226 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.029           ms/op
ClientPb.getUser:getUser·p0.9999        sample          19.530           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.118           ms/op
ClientPb.listUser                       sample  247397   3.879 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.762           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.592           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.931           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
