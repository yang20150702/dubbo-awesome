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
# Warmup Iteration   1: 5.083 ops/ms
# Warmup Iteration   2: 12.441 ops/ms
# Warmup Iteration   3: 12.633 ops/ms
Iteration   1: 12.769 ops/ms
Iteration   2: 13.034 ops/ms
Iteration   3: 12.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.914 ±(99.9%) 2.450 ops/ms [Average]
  (min, avg, max) = (12.769, 12.914, 13.034), stdev = 0.134
  CI (99.9%): [10.465, 15.364] (assumes normal distribution)


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
# Warmup Iteration   1: 8.472 ops/ms
# Warmup Iteration   2: 13.401 ops/ms
# Warmup Iteration   3: 13.088 ops/ms
Iteration   1: 13.477 ops/ms
Iteration   2: 13.412 ops/ms
Iteration   3: 13.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.382 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (13.258, 13.382, 13.477), stdev = 0.112
  CI (99.9%): [11.333, 15.432] (assumes normal distribution)


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
# Warmup Iteration   1: 8.082 ops/ms
# Warmup Iteration   2: 12.975 ops/ms
# Warmup Iteration   3: 13.094 ops/ms
Iteration   1: 13.213 ops/ms
Iteration   2: 13.297 ops/ms
Iteration   3: 13.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.181 ±(99.9%) 2.475 ops/ms [Average]
  (min, avg, max) = (13.032, 13.181, 13.297), stdev = 0.136
  CI (99.9%): [10.706, 15.656] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.888 ops/ms
# Warmup Iteration   2: 10.711 ops/ms
# Warmup Iteration   3: 10.755 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.812 ops/ms
Iteration   3: 10.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.797 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (10.772, 10.797, 10.812), stdev = 0.021
  CI (99.9%): [10.406, 11.188] (assumes normal distribution)


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.461 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.448, 2.461, 2.477), stdev = 0.015
  CI (99.9%): [2.190, 2.732] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.561 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.004 ms/op
Iteration   1: 2.402 ±(99.9%) 0.004 ms/op
Iteration   2: 2.395 ±(99.9%) 0.004 ms/op
Iteration   3: 2.387 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.395 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.387, 2.395, 2.402), stdev = 0.007
  CI (99.9%): [2.263, 2.526] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.004 ms/op
Iteration   2: 2.419 ±(99.9%) 0.003 ms/op
Iteration   3: 2.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.432 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.419, 2.432, 2.449), stdev = 0.016
  CI (99.9%): [2.146, 2.717] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.523 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
Iteration   3: 2.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (2.974, 2.979, 2.983), stdev = 0.005
  CI (99.9%): [2.896, 3.061] (assumes normal distribution)


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  6.818 ms/op
                 createUser·p0.9999: 12.909 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  7.040 ms/op
                 createUser·p0.9999: 11.994 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 11.634 ms/op
                 createUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389495
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 192513 
    [ 2.500,  3.750) = 193788 
    [ 3.750,  5.000) = 2539 
    [ 5.000,  6.250) = 133 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     12.436 ms/op
     p(99.9990) =     13.387 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.388 ±(99.9%) 0.005 ms/op
Iteration   1: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  5.641 ms/op
                 existUser·p0.9999: 13.588 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  7.624 ms/op
                 existUser·p0.9999: 12.567 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  7.952 ms/op
                 existUser·p0.9999: 11.010 ms/op
                 existUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399882
  mean =      2.399 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 204799 
    [ 2.500,  3.750) = 191678 
    [ 3.750,  5.000) = 2264 
    [ 5.000,  6.250) = 584 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     13.779 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  7.943 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  7.419 ms/op
                 getUser·p0.9999: 12.104 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  6.522 ms/op
                 getUser·p0.9999: 11.649 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388159
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 194191 
    [ 2.500,  3.750) = 189148 
    [ 3.750,  5.000) = 3764 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      6.592 ms/op
     p(99.9900) =     12.818 ms/op
     p(99.9990) =     13.783 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.646 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
Iteration   1: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.204 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.879 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.002 ms/op
                 listUser·p0.9999: 10.994 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320795
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 96254 
    [ 2.500,  3.750) = 186829 
    [ 3.750,  5.000) = 30555 
    [ 5.000,  6.250) = 5584 
    [ 6.250,  7.500) = 767 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.618 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.914 ± 2.450  ops/ms
ClientPb.existUser                       thrpt       3  13.382 ± 2.049  ops/ms
ClientPb.getUser                         thrpt       3  13.181 ± 2.475  ops/ms
ClientPb.listUser                        thrpt       3  10.797 ± 0.391  ops/ms
ClientPb.createUser                       avgt       3   2.461 ± 0.271   ms/op
ClientPb.existUser                        avgt       3   2.395 ± 0.131   ms/op
ClientPb.getUser                          avgt       3   2.432 ± 0.286   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.083   ms/op
ClientPb.createUser                     sample  389495   2.462 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.939           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.523           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.436           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  399882   2.399 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.946           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.910           ms/op
ClientPb.getUser                        sample  388159   2.471 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.592           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.818           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.910           ms/op
ClientPb.listUser                       sample  320795   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.830           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.043           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.026           ms/op
