# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.417 ops/ms
# Warmup Iteration   2: 5.501 ops/ms
# Warmup Iteration   3: 7.284 ops/ms
Iteration   1: 7.545 ops/ms
Iteration   2: 7.316 ops/ms
Iteration   3: 7.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.546 ±(99.9%) 4.213 ops/ms [Average]
  (min, avg, max) = (7.316, 7.546, 7.778), stdev = 0.231
  CI (99.9%): [3.333, 11.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.359 ops/ms
# Warmup Iteration   2: 7.394 ops/ms
# Warmup Iteration   3: 7.921 ops/ms
Iteration   1: 7.757 ops/ms
Iteration   2: 7.917 ops/ms
Iteration   3: 7.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.764 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (7.619, 7.764, 7.917), stdev = 0.150
  CI (99.9%): [5.036, 10.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ops/ms
# Warmup Iteration   2: 7.157 ops/ms
# Warmup Iteration   3: 7.337 ops/ms
Iteration   1: 7.018 ops/ms
Iteration   2: 7.386 ops/ms
Iteration   3: 7.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.316 ±(99.9%) 4.932 ops/ms [Average]
  (min, avg, max) = (7.018, 7.316, 7.545), stdev = 0.270
  CI (99.9%): [2.384, 12.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.000 ops/ms
# Warmup Iteration   2: 5.265 ops/ms
# Warmup Iteration   3: 5.825 ops/ms
Iteration   1: 6.155 ops/ms
Iteration   2: 6.094 ops/ms
Iteration   3: 5.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.079 ±(99.9%) 1.549 ops/ms [Average]
  (min, avg, max) = (5.987, 6.079, 6.155), stdev = 0.085
  CI (99.9%): [4.530, 7.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.589 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.003 ms/op
Iteration   1: 4.259 ±(99.9%) 0.003 ms/op
Iteration   2: 4.337 ±(99.9%) 0.003 ms/op
Iteration   3: 4.285 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.294 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (4.259, 4.294, 4.337), stdev = 0.039
  CI (99.9%): [3.573, 5.014] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.653 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.004 ms/op
Iteration   1: 4.003 ±(99.9%) 0.003 ms/op
Iteration   2: 4.074 ±(99.9%) 0.003 ms/op
Iteration   3: 3.950 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.009 ±(99.9%) 1.130 ms/op [Average]
  (min, avg, max) = (3.950, 4.009, 4.074), stdev = 0.062
  CI (99.9%): [2.879, 5.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.879 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.470 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.005 ms/op
Iteration   1: 4.206 ±(99.9%) 0.003 ms/op
Iteration   2: 4.280 ±(99.9%) 0.003 ms/op
Iteration   3: 4.146 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.210 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (4.146, 4.210, 4.280), stdev = 0.067
  CI (99.9%): [2.981, 5.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.221 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.611 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.538 ±(99.9%) 0.013 ms/op
Iteration   1: 5.417 ±(99.9%) 0.022 ms/op
Iteration   2: 5.231 ±(99.9%) 0.011 ms/op
Iteration   3: 5.147 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.265 ±(99.9%) 2.524 ms/op [Average]
  (min, avg, max) = (5.147, 5.265, 5.417), stdev = 0.138
  CI (99.9%): [2.741, 7.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.956 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.013 ms/op
Iteration   1: 4.175 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.454 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   8.151 ms/op
                 createUser·p0.999:  13.025 ms/op
                 createUser·p0.9999: 15.335 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 4.214 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  14.928 ms/op
                 createUser·p0.9999: 18.562 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   3: 4.108 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  13.488 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 230449
  mean =      4.165 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5877 
    [ 2.500,  5.000) = 191649 
    [ 5.000,  7.500) = 30611 
    [ 7.500, 10.000) = 1741 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     22.814 ms/op
     p(99.9990) =     23.639 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.013 ms/op
Iteration   1: 4.122 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.734 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  12.072 ms/op
                 existUser·p0.9999: 15.450 ms/op
                 existUser·p1.00:   16.171 ms/op

Iteration   2: 3.911 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  12.616 ms/op
                 existUser·p0.9999: 20.238 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  10.834 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236899
  mean =      4.054 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9151 
    [ 2.500,  5.000) = 197801 
    [ 5.000,  7.500) = 27806 
    [ 7.500, 10.000) = 1601 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     12.191 ms/op
     p(99.9900) =     19.671 ms/op
     p(99.9990) =     21.156 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.259 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.477 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.015 ms/op
Iteration   1: 4.226 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   4.104 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.564 ms/op
                 getUser·p0.999:  12.163 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   2: 4.298 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 22.792 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 4.091 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  13.678 ms/op
                 getUser·p0.9999: 31.425 ms/op
                 getUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228208
  mean =      4.203 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4205 
    [ 2.500,  5.000) = 192969 
    [ 5.000,  7.500) = 29051 
    [ 7.500, 10.000) = 1433 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     30.855 ms/op
     p(99.9990) =     32.431 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.837 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.855 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.363 ±(99.9%) 0.019 ms/op
Iteration   1: 5.319 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  14.334 ms/op
                 listUser·p0.9999: 18.656 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 5.226 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.174 ms/op
                 listUser·p0.999:  20.932 ms/op
                 listUser·p0.9999: 26.473 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 5.245 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 32.031 ms/op
                 listUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182419
  mean =      5.263 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 299 
    [ 2.500,  5.000) = 91248 
    [ 5.000,  7.500) = 79062 
    [ 7.500, 10.000) = 10227 
    [10.000, 12.500) = 1159 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.823 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     30.106 ms/op
     p(99.9990) =     32.889 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.546 ± 4.213  ops/ms
ClientGrpc.existUser                       thrpt       3   7.764 ± 2.729  ops/ms
ClientGrpc.getUser                         thrpt       3   7.316 ± 4.932  ops/ms
ClientGrpc.listUser                        thrpt       3   6.079 ± 1.549  ops/ms
ClientGrpc.createUser                       avgt       3   4.294 ± 0.721   ms/op
ClientGrpc.existUser                        avgt       3   4.009 ± 1.130   ms/op
ClientGrpc.getUser                          avgt       3   4.210 ± 1.230   ms/op
ClientGrpc.listUser                         avgt       3   5.265 ± 2.524   ms/op
ClientGrpc.createUser                     sample  230449   4.165 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.454           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.059           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.218           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.620           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.504           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.271           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.814           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  236899   4.054 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.958           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.965           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.324           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.191           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.671           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  228208   4.203 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.853           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.266           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.648           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.855           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.506           ms/op
ClientGrpc.listUser                       sample  182419   5.263 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.180           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.823           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.798           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.106           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.997           ms/op
