# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 5.848 ops/ms
# Warmup Iteration   3: 8.706 ops/ms
Iteration   1: 9.499 ops/ms
Iteration   2: 9.060 ops/ms
Iteration   3: 9.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.301 ±(99.9%) 4.070 ops/ms [Average]
  (min, avg, max) = (9.060, 9.301, 9.499), stdev = 0.223
  CI (99.9%): [5.232, 13.371] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 8.785 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 9.681 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 9.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.802 ±(99.9%) 3.414 ops/ms [Average]
  (min, avg, max) = (9.681, 9.802, 10.017), stdev = 0.187
  CI (99.9%): [6.388, 13.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.274 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 9.057 ops/ms
Iteration   1: 9.458 ops/ms
Iteration   2: 9.195 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.376 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (9.195, 9.376, 9.474), stdev = 0.156
  CI (99.9%): [6.521, 12.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.717 ops/ms
# Warmup Iteration   2: 7.602 ops/ms
# Warmup Iteration   3: 8.179 ops/ms
Iteration   1: 8.055 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.148 ±(99.9%) 1.770 ops/ms [Average]
  (min, avg, max) = (8.055, 8.148, 8.249), stdev = 0.097
  CI (99.9%): [6.377, 9.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.704 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.005 ms/op
Iteration   1: 3.412 ±(99.9%) 0.006 ms/op
Iteration   2: 3.308 ±(99.9%) 0.011 ms/op
Iteration   3: 3.381 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.367 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.308, 3.367, 3.412), stdev = 0.053
  CI (99.9%): [2.399, 4.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.052 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.008 ms/op
Iteration   1: 3.322 ±(99.9%) 0.007 ms/op
Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
Iteration   3: 3.162 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.255 ±(99.9%) 1.524 ms/op [Average]
  (min, avg, max) = (3.162, 3.255, 3.322), stdev = 0.084
  CI (99.9%): [1.732, 4.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.401 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.005 ms/op
Iteration   1: 3.411 ±(99.9%) 0.005 ms/op
Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
Iteration   3: 3.510 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.426 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (3.358, 3.426, 3.510), stdev = 0.077
  CI (99.9%): [2.025, 4.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.694 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.012 ms/op
Iteration   2: 3.802 ±(99.9%) 0.014 ms/op
Iteration   3: 3.808 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.824 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.802, 3.824, 3.862), stdev = 0.033
  CI (99.9%): [3.225, 4.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.921 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
Iteration   1: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 23.078 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  20.729 ms/op
                 createUser·p0.9999: 24.097 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  19.497 ms/op
                 createUser·p0.9999: 24.786 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282560
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3600 
    [ 2.500,  5.000) = 271784 
    [ 5.000,  7.500) = 5792 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 163 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     19.708 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     25.991 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.646 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.008 ms/op
Iteration   1: 3.375 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  8.819 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  12.134 ms/op
                 existUser·p0.9999: 25.646 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  17.911 ms/op
                 existUser·p0.9999: 24.555 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290857
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11767 
    [ 2.500,  5.000) = 273544 
    [ 5.000,  7.500) = 4528 
    [ 7.500, 10.000) = 575 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     25.226 ms/op
     p(99.9990) =     26.810 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.926 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
Iteration   1: 3.394 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  17.786 ms/op
                 getUser·p0.9999: 20.485 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  18.936 ms/op
                 getUser·p0.9999: 22.764 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 3.414 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  21.552 ms/op
                 getUser·p0.9999: 25.097 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280945
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5961 
    [ 2.500,  5.000) = 265101 
    [ 5.000,  7.500) = 8421 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     18.221 ms/op
     p(99.9900) =     23.852 ms/op
     p(99.9990) =     25.456 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.980 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.014 ms/op
Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  22.111 ms/op
                 listUser·p0.9999: 30.900 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   2: 4.039 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 18.075 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 28.415 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241615
  mean =      3.974 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 234360 
    [ 5.000,  7.500) = 5107 
    [ 7.500, 10.000) = 1271 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     32.738 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.301 ± 4.070  ops/ms
ClientPb.existUser                       thrpt       3   9.802 ± 3.414  ops/ms
ClientPb.getUser                         thrpt       3   9.376 ± 2.855  ops/ms
ClientPb.listUser                        thrpt       3   8.148 ± 1.770  ops/ms
ClientPb.createUser                       avgt       3   3.367 ± 0.968   ms/op
ClientPb.existUser                        avgt       3   3.255 ± 1.524   ms/op
ClientPb.getUser                          avgt       3   3.426 ± 1.401   ms/op
ClientPb.listUser                         avgt       3   3.824 ± 0.599   ms/op
ClientPb.createUser                     sample  282560   3.393 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.724           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  290857   3.297 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.534           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.226           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  280945   3.413 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.861           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.221           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.852           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.018           ms/op
ClientPb.listUser                       sample  241615   3.974 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.688           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.834           ms/op
