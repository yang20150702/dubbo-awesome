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
# Warmup Iteration   1: 2.208 ops/ms
# Warmup Iteration   2: 5.723 ops/ms
# Warmup Iteration   3: 8.646 ops/ms
Iteration   1: 9.184 ops/ms
Iteration   2: 9.019 ops/ms
Iteration   3: 8.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.040 ±(99.9%) 2.450 ops/ms [Average]
  (min, avg, max) = (8.918, 9.040, 9.184), stdev = 0.134
  CI (99.9%): [6.591, 11.490] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 8.912 ops/ms
# Warmup Iteration   3: 9.361 ops/ms
Iteration   1: 9.713 ops/ms
Iteration   2: 9.527 ops/ms
Iteration   3: 9.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.676 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (9.527, 9.676, 9.786), stdev = 0.133
  CI (99.9%): [7.242, 12.109] (assumes normal distribution)


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
# Warmup Iteration   1: 2.810 ops/ms
# Warmup Iteration   2: 8.465 ops/ms
# Warmup Iteration   3: 8.904 ops/ms
Iteration   1: 9.217 ops/ms
Iteration   2: 9.242 ops/ms
Iteration   3: 9.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.230 ±(99.9%) 0.229 ops/ms [Average]
  (min, avg, max) = (9.217, 9.230, 9.242), stdev = 0.013
  CI (99.9%): [9.001, 9.459] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.813 ops/ms
# Warmup Iteration   2: 7.253 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 7.638 ops/ms
Iteration   2: 7.840 ops/ms
Iteration   3: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.813 ±(99.9%) 2.990 ops/ms [Average]
  (min, avg, max) = (7.638, 7.813, 7.962), stdev = 0.164
  CI (99.9%): [4.824, 10.803] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.049 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.004 ms/op
Iteration   1: 3.549 ±(99.9%) 0.005 ms/op
Iteration   2: 3.490 ±(99.9%) 0.004 ms/op
Iteration   3: 3.401 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.480 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.401, 3.480, 3.549), stdev = 0.075
  CI (99.9%): [2.115, 4.845] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.572 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.002 ms/op
Iteration   1: 3.312 ±(99.9%) 0.003 ms/op
Iteration   2: 3.250 ±(99.9%) 0.005 ms/op
Iteration   3: 3.283 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.282 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (3.250, 3.282, 3.312), stdev = 0.031
  CI (99.9%): [2.718, 3.845] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.589 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.004 ms/op
Iteration   1: 3.471 ±(99.9%) 0.005 ms/op
Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
Iteration   3: 3.590 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.519 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (3.471, 3.519, 3.590), stdev = 0.063
  CI (99.9%): [2.375, 4.663] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.791 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.005 ms/op
Iteration   1: 4.080 ±(99.9%) 0.008 ms/op
Iteration   2: 4.075 ±(99.9%) 0.005 ms/op
Iteration   3: 4.123 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.093 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (4.075, 4.093, 4.123), stdev = 0.026
  CI (99.9%): [3.610, 4.576] (assumes normal distribution)


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
# Warmup Iteration   1: 9.958 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.008 ms/op
Iteration   1: 3.456 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  17.496 ms/op
                 createUser·p0.9999: 20.963 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.443 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.109 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  19.799 ms/op
                 createUser·p0.9999: 25.117 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.415 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  16.136 ms/op
                 createUser·p0.9999: 23.778 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278963
  mean =      3.438 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12799 
    [ 2.500,  5.000) = 262304 
    [ 5.000,  7.500) = 2708 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     17.106 ms/op
     p(99.9900) =     24.219 ms/op
     p(99.9990) =     25.816 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 8.709 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.008 ms/op
Iteration   1: 3.342 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  18.497 ms/op
                 existUser·p0.9999: 22.460 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.337 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  20.485 ms/op
                 existUser·p0.9999: 26.151 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.413 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 27.862 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288873
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9869 
    [ 2.500,  5.000) = 273622 
    [ 5.000,  7.500) = 4106 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     26.284 ms/op
     p(99.9990) =     28.111 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 10.099 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.010 ms/op
Iteration   1: 3.588 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.593 ms/op
                 getUser·p0.999:  14.696 ms/op
                 getUser·p0.9999: 20.355 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   2: 3.443 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  17.476 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   3: 3.480 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.222 ms/op
                 getUser·p0.999:  17.864 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273801
  mean =      3.502 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1947 
    [ 2.500,  5.000) = 266270 
    [ 5.000,  7.500) = 4299 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     15.788 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 11.676 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.013 ms/op
Iteration   1: 4.089 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  19.878 ms/op
                 listUser·p0.9999: 24.174 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 4.082 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.462 ms/op
                 listUser·p0.9999: 20.153 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.202 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 18.428 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232652
  mean =      4.124 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 224385 
    [ 5.000,  7.500) = 6341 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     22.435 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.040 ± 2.450  ops/ms
ClientPb.existUser                       thrpt       3   9.676 ± 2.433  ops/ms
ClientPb.getUser                         thrpt       3   9.230 ± 0.229  ops/ms
ClientPb.listUser                        thrpt       3   7.813 ± 2.990  ops/ms
ClientPb.createUser                       avgt       3   3.480 ± 1.365   ms/op
ClientPb.existUser                        avgt       3   3.282 ± 0.564   ms/op
ClientPb.getUser                          avgt       3   3.519 ± 1.144   ms/op
ClientPb.listUser                         avgt       3   4.093 ± 0.483   ms/op
ClientPb.createUser                     sample  278963   3.438 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.743           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.219           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  288873   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.413           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.664           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.284           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  273801   3.502 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.163           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.788           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.987           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.364           ms/op
ClientPb.listUser                       sample  232652   4.124 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.239           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.811           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.576           ms/op
